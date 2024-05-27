# What are forms?

Forms play a crucial role in enabling various online activities, such as making online purchases and logging into websites. They allow users to enter and submit data to the server.

The video starts by explaining the basic structure of a form using the `<form>` tags. It also introduces the optional `action` attribute, which specifies the URL or path that the form should submit the data to. If the `action` attribute is not specified, the form will submit the data to the same path as the current web page.

Next, the video covers the `method` attribute, which determines the HTTP method to be used for submitting the form data. The two commonly used methods are `GET` and `POST`. The `GET` method is used to retrieve information from the server, while the `POST` method is used to send data to the server.

Moving on, the video explores different input types that can be added to a form. It starts with a simple text field, which is created using the `<input>` tag with the `type` attribute set to "text". The video also demonstrates how to add a label above the input field using the `<label>` tag.

The video then introduces a password field, which is created using the `<input>` tag with the `type` attribute set to "password". This input type masks the user's input data, ensuring that the password remains hidden.

To enable form submission, the video shows how to add a submit button using the `<input>` tag with the `type` attribute set to "submit". When the user clicks the submit button, the form data is sent to the web server.

The video also covers other input types, such as checkboxes, radio buttons, text areas, and drop-down lists. It explains how to use the respective HTML tags (`<input>`, `<textarea>`, `<select>`, and `<option>`) to create these input types and configure their behavior.

By the end of the video, you will have a solid understanding of how HTML forms work and how to create various input types within a form. This knowledge will empower you to design and implement user-friendly forms for your web development projects.

## Input Examples

In addition to the input types mentioned in the video, there are several other input types that can be used in an HTML form. Here are some examples:

1. **Number**: This input type allows users to enter numeric values. It can be created using the `<input>` tag with the `type` attribute set to "number". This input type can also have additional attributes like `min` and `max` to specify the range of acceptable values.

2. **Email**: This input type is specifically designed for email addresses. It can be created using the `<input>` tag with the `type` attribute set to "email". This input type provides built-in validation to ensure that the entered value is a valid email address.

3. **Date**: This input type allows users to select a date from a calendar. It can be created using the `<input>` tag with the `type` attribute set to "date". This input type provides a user-friendly interface for selecting dates.

4. **File**: This input type enables users to upload files from their local system. It can be created using the `<input>` tag with the `type` attribute set to "file". When the user selects a file, the form data will include the file's contents.

5. **Color**: This input type allows users to select a color from a color picker. It can be created using the `<input>` tag with the `type` attribute set to "color". This input type provides a visual interface for choosing colors.

6. **Range**: This input type allows users to select a value from a specified range. It can be created using the `<input>` tag with the `type` attribute set to "range". You can specify the minimum and maximum values using the `min` and `max` attributes.

7. **URL**: This input type is used for entering website URLs. It can be created using the `<input>` tag with the `type` attribute set to "url". This input type provides built-in validation to ensure that the entered value is a valid URL.

8. **Time**: This input type allows users to select a specific time. It can be created using the `<input>` tag with the `type` attribute set to "time". This input type provides a user-friendly interface for selecting time values.

9. **Search**: This input type is used for search input fields. It can be created using the `<input>` tag with the `type` attribute set to "search". This input type often includes a search icon or magnifying glass to indicate its purpose.

10. **Tel**: This input type is used for entering telephone numbers. It can be created using the `<input>` tag with the `type` attribute set to "tel". This input type can provide additional features like input masking or validation for phone number formats.

11. **Checkbox**: Although mentioned in the video, it's worth highlighting that checkboxes can be used to allow users to select multiple options from a list. Each checkbox is created using the `<input>` tag with the `type` attribute set to "checkbox".

These are just a few examples of the input types available in HTML forms. Each input type has its own purpose and behavior, allowing you to collect specific types of data from users. You can explore more input types and their attributes in the HTML documentation or in further courses on web development.

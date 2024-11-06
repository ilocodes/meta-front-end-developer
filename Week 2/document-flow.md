# Document flow - block vs. inline

The web browser uses a method called document flow to determine the positioning of HTML elements on the screen.

## Block vs. Inline Elements

### Block Elements

- Occupy the full horizontal width of their parent element.
- The height is determined by their content.
- Always start on a new line, creating a stack of elements like boxes.
- Examples include `<div>`, `<form>`, and heading tags (`<h1>`, `<h2>`, etc.).

### Inline Elements

- Occupy only as much width and height as their content needs.
- Do not start on a new line; they flow within the text.
- Examples include `<a>`, `<img>`, `<input>`, `<label>`, `<b>`, `<i>`, `<em>`, and `<span>`.

## Practical Demonstration

A practical example using Visual Studio Code:

1. An HTML file with a `<div>` element containing three sentences of placeholder text (Lorem Ipsum).
2. Each sentence is wrapped in a `<span>` element (inline).
3. Changing the middle `<span>` to a `<div>` demonstrates how block elements create new lines.
4. The result shows the middle sentence on a new line, and the sentence after it on another new line.

## Changing Element Display Property

Using CSS, the display property can change an element from block to inline and vice versa.

1. Adding a CSS file (`style.css`) and using an ID to target the middle sentence's `<div>` element:
    - Setting `display: inline;` makes the `<div>` act as an inline element.
    - Removing the property reverts it to a block element.
    - Setting `display: block;` confirms it as a block element.
2. Other values for the display property can change an element's layout behavior.

# Developer Tools

Most web browsers come with developer tools that help developers inspect their HTML, CSS, and JavaScript code, trace HTTP requests to the web server, investigate performance issues, and review web page security. Let's explore these tools using the homepage of the Little Lemon Cafe.

To start, I opened the Little Lemon Cafe's webpage in my Chrome browser. I can see their menu on the homepage, but I want to examine the HTML structure of this menu. To do this, I need to open the developer tools.

### Opening Developer Tools in Chrome
- **PC**: Press the `F12` key.
- **Mac**: Press `Command + Option + J`.
- Alternatively, right-click on the webpage and select "Inspect".

### Developer Tools Tabs Overview
- **Console Tab**: Displays JavaScript logs and errors.
- **Sources Tab**: Shows all content for the current page, including HTML, CSS, JavaScript, images, and videos.
- **Network Tab**: Inspects the timeline and details of HTTP requests and responses.
- **Performance Tab**: Displays what the browser is doing over time, helping you identify slow-running functions.
- **Memory Tab**: Shows which parts of your code are using the most resources.
- **Elements Tab**: Allows you to inspect HTML elements and their properties. Hovering over an element highlights it in the browser.

### Inspecting Elements and CSS
On the right side of the panel, you can inspect element details further. This shows the CSS applied to an element and its display result in the browser. We'll explore these details later. For now, know that clicking on an HTML element displays its information in the tab.

### Fun Trick
You can edit HTML directly in the browser. For example, if I double-click the "Our Menu" element, I can change "Chicken Burger" to "Turkey Burger". This change is only temporary and doesn't affect the server. When you reload the page, it resets.

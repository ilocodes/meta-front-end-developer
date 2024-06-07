# Introduction to HTML, CSS and Javascript
The web pages you visit every day are built with three core technologies: HTML, CSS, and JavaScript. Together, they enable the creation of web pages and applications, allowing you to offer any content you see online.

### Example 1: Digital Clock

I'm creating a web page that shows a digital clock displaying hours, minutes, and seconds, updated every second. I'll use three files: HTML, CSS, and JavaScript. Let's explore their purposes:

1. **HTML (clock.html)**: Defines the structure of the clock, displaying the content in hours, minutes, and seconds. Without styling, it would just show six zeros (00:00:00).
2. **CSS (styles.css)**: Adds styles to the HTML element. It positions, sizes, colors, and styles the clock. The browser processes this file to display the clock properly.
3. **JavaScript (clock.js)**: Ensures the clock updates every second. The browser processes this file to dynamically update the hour, minute, and second elements.

With these three files linked together, the clock is fully functional. This demonstrates how JavaScript dynamically updates content.

### Example 2: Interactive Video Player

I'm building a web page that plays a video with a button to play or pause the video. Here's how it works:

1. **HTML**: Describes the video element and the Play button.
2. **CSS**: Styles the video and button.
3. **JavaScript (videoplayer.js)**: Makes the button interactive. It performs four actions:
   - Registers a listener on the button to execute code when clicked.
   - Checks the current state of the video.
   - If the video is stopped, it plays the video and changes the button to a stop icon.
   - If the video is playing, it stops the video and changes the button to a play icon.

When the user first sees the page, the video is stopped by default. Clicking the Play button starts the video and changes the button to a stop icon. Clicking the button again stops the video and changes the button back to a play icon.

Using these three files, you create a fully interactive video player.


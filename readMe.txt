Certainly! Below is a simple README file for your HTML project:

---

# Interactive Rectangle Color Change

This project demonstrates an interactive rectangle that changes color based on mouse movements within the rectangle. The project uses HTML, CSS, and the GreenSock Animation Platform (GSAP) library for the animations.

## Files

- `index.html`: The main HTML file containing the structure of the project.
- `style.css`: The CSS file for styling the HTML content.
- `script.js`: The JavaScript file handling the interactive color change based on mouse movements.

## How to Run

1. Open the `index.html` file in a web browser.

## Project Structure

### HTML Structure

- The HTML file contains a `div` element with the id `center`, representing the interactive rectangle.

### CSS Styling

- The `style.css` file provides basic styling for the HTML document, setting margins, padding, and a specific font family.
- The `#center` CSS selector styles the interactive rectangle, positioning it in the center of the viewport with a specified width, height, and a border.

### JavaScript Interaction

- The `script.js` file contains JavaScript code using the GSAP library.
- The script listens for `mousemove` events on the rectangle (`#center`) and adjusts the background color dynamically based on the mouse position.
- When the mouse leaves the rectangle, the background color smoothly transitions back to white.

## Dependencies

- [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/): The library is included via a CDN to enable smooth animations.

## Additional Notes

- Adjust the dimensions of the `#center` element in the CSS file to modify the size of the interactive rectangle.
- Ensure an active internet connection to fetch the GSAP library from the CDN.

Feel free to explore, modify, and enhance the project to suit your needs!

---


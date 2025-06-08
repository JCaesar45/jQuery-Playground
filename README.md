```markdown
# jQuery Playground

This is a simple web page demonstrating basic jQuery DOM manipulation and animations using Bootstrap and Animate.css.

---

## Overview

The page contains two sections (`#left-well` and `#right-well`), each with several buttons. Using jQuery, the script performs various DOM manipulations and adds CSS animations when the document is ready.

---

## Features Demonstrated

- Changing CSS styles of specific elements.
- Enabling/disabling buttons.
- Removing elements from the DOM.
- Moving elements between containers.
- Cloning elements.
- Changing parent element styles.
- Applying color styles to children elements.
- Using jQuery selectors (`:nth-child`, `:even`).
- Adding Animate.css classes to elements to trigger animations.

---

## Libraries Used

- [jQuery 3.6.0](https://code.jquery.com/jquery-3.6.0.min.js)
- [Bootstrap 3.3.7](https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css)
- [Animate.css 3.7.2](https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css)

---

## How It Works

- **`#target1`** text color is set to red and the button is disabled.
- **`#target4`** button is removed from the page.
- **`#target2`** button is moved from `#left-well` to `#right-well`.
- **`#target5`** button is cloned and appended to `#left-well`.
- The background color of the parent container of `#target1` (`#left-well`) is changed to red.
- All children in `#right-well` have their text color changed to orange.
- All children in `#left-well` have their text color changed to green.
- The second `.target` button on the page gets the Animate.css classes `animated bounce`.
- Every even `.target` button gets the classes `animated shake`.
- The `<body>` element gets Animate.css classes `animated hinge` which triggers a hinge animation on the entire page.

---

## How to Run

1. Save the HTML code in a file (e.g., `index.html`).
2. Open the file in any modern web browser.
3. Observe the DOM manipulations and animations applied after the page loads.

---

## Notes

- The Animate.css animations will run immediately on page load.
- The example uses Bootstrap 3 grid system for layout.
- The jQuery selectors showcase common DOM traversal and manipulation techniques.

---

## License

This project is open source and free to use.

---

Feel free to customize and extend this playground for your jQuery learning purposes!
```

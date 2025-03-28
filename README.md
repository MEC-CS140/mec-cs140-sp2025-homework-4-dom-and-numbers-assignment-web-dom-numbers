# CS 140: Homework - Alert with Numbers

🔎🔍🔎🔍 [See the example here](https://purple-sand-0cee30710.4.azurestaticapps.net)

## Instructions
Create a webpage with a button that triggers an alert when clicked. The alert will display a number that increases with each button click. For extra credit, the alert will also print whether the number is even or odd.

### Setup
- Add a button that the user can click.
- Use a <script> tag to include your JavaScript in the same HTML file.

### Control the number variable

- Initialize a number variable that starts at 0.
- Every time the button is pressed, the number should increase by 1.

### Trigger an alert

- Use the alert() function to display the number each time the button is pressed.

### (Optional - Extra Credit):

- Check if the number is even or odd.
- Add the result (either "even" or "odd") into the alert message (hint, you can use concatenation or [template literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals) to do this).


### **JavaScript Button Alert Assignment Rubric**

| Criteria                               | Excellent (5 points)                    | Good (4 points)                        | Satisfactory (3 points)               | Needs Improvement (2 points)          | Incomplete (0-1 points)                | Points |
|----------------------------------------|-----------------------------------------|----------------------------------------|---------------------------------------|----------------------------------------|-----------------------------------------|--------|
| **HTML Structure**                     | Button element added. Clear structure, no issues with tags or formatting. | Button present, minor issues with formatting but works fine. | HTML structure has some issues but doesn’t prevent functionality. | HTML structure is incorrect or severely impacts the functionality. | Missing button or HTML structure prevents functionality. |   /5   |
| **Number Variable Initialization**     | Number variable properly initialized and updates correctly with each button press. | Number variable works, minor issues with initialization or updates. | Number variable mostly works but shows irregular behavior. | Variable exists but doesn’t update correctly with each click. | No variable or incorrect variable usage; button does not affect variable. |   /5   |
| **Button Click Functionality**         | Button successfully triggers an alert, displaying the incremented number each time. | Button works but minor issues with the alert or update logic. | Button mostly works, but alert or number doesn’t always update correctly. | Button exists but has major issues, preventing alert from working as expected. | Button does not trigger any action or alert. |   /5   |
| **Alert Message Content**              | Alert shows the correct number and is well formatted. | Alert shows the correct number with minor formatting issues. | Alert shows the number but has some issues with clarity or correctness. | Alert is unclear or shows the wrong number due to logic errors. | No alert or incorrect alert content that does not show the number. |   /5   |
| **Extra Credit: Even/Odd Check** (Bonus) | Clearly and correctly identifies whether the number is even or odd, displaying this in the alert message. | Even/odd check mostly works with minor issues in output or logic. | Even/odd check present but irregular, sometimes displays wrong result. | Even/odd check attempted but does not work correctly. | No attempt. |   /5   |
---

## Handy Tags, CSS Rules, and JavaScript Snippets

### HTML Tags to Remember

| Tag        | Description                           | Example                                 |
|------------|---------------------------------------|-----------------------------------------|
| `<a>`      | Creates a hyperlink to another page.  | `<a href="https://example.com">Visit!</a>` |
| `<img>`    | Embeds an image in your webpage.      | `<img src="image.jpg" alt="A cool image">` |
| `<ul>`, `<li>` | Creates a list of items.             | `<ul><li>Item 1</li><li>Item 2</li></ul>`   |
| `<div>`    | Defines a division or section.        | `<div>Content here</div>`               |

### CSS Rules to Spice Up Your Site

| Rule              | Description                                | Example                               |
|-------------------|--------------------------------------------|---------------------------------------|
| `font-family`     | Changes the font of your text.             | `font-family: 'Arial', sans-serif;`   |
| `margin`, `padding` | Controls the space around and inside elements. | `margin: 10px; padding: 20px;`        |
| `border`          | Adds a border around elements.             | `border: 2px solid #000;`             |
| `background-color`| Sets the background color of elements.     | `background-color: #ffcc00;`          |

### JavaScript Snippets for Interactivity

- **Show an Alert**:
  - `alert('Welcome to CS 140 Web Development!');`
- **Change Text Content**:
  - Example: `document.getElementById('exampleId').textContent = 'Hello, CS 140!';`
- **Add a Click Event**:
  - Example:
    ```javascript
    document.getElementById('clickMeButton').addEventListener('click', function() {
        alert('You clicked the button!');
    });
    ```

*This document was initially drafted with the help of ChatGPT. It has been edited and customized to fit our class's needs.
*

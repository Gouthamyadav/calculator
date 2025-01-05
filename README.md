
# Simple Calculator

A simple **calculator** built using **HTML**, **CSS**, and **JavaScript**. This calculator can perform basic arithmetic operations such as addition, subtraction, multiplication, and division. It also includes functionality for clearing the history, backspacing, and formatting numbers.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Clear**: Clears the history and current output.
- **Backspace**: Deletes the last entered number or operator.
- **Formatted Output**: The result is displayed with comma-separated thousands for easier readability.
- **History Display**: Keeps track of the entered operations.
- **Responsive Design**: Works well on both mobile and desktop browsers.

## Technologies Used

- **HTML**: Provides the basic structure of the calculator interface, including buttons and displays.
- **CSS**: Styles the calculator layout, ensuring it looks clean and responsive.
- **JavaScript**: Handles the logic for operations, including managing user input, history, and calculating results.

## How It Works

1. **HTML Structure**:
   - The calculator consists of an output display for showing results and a history area for displaying the operations entered.
   - Buttons are organized into number buttons (0-9), operator buttons (+, -, *, /), and special buttons (Clear, Backspace, Equals).

2. **CSS Styling**:
   - The buttons are styled to be easy to click and the layout is responsive, ensuring a good user experience on various screen sizes.
   - The output display shows the result and is updated as the user enters numbers and operators.

3. **JavaScript Functionality**:
   - **getHistory()**: Retrieves the current operation history.
   - **printHistory(num)**: Displays the operation history in the history display.
   - **getOutput()**: Retrieves the current output value.
   - **printOutput(num)**: Displays the current output value, formatted with commas.
   - **getFormattedNumber(num)**: Formats the output number with commas for thousands separation.
   - **reverseNumberFormat(num)**: Converts the formatted output back into a plain number (removes commas).
   - Event listeners are added to all the buttons (numbers and operators). When clicked, the appropriate action is taken, such as updating the output or history, performing calculations, or clearing/backspacing.

4. **Operations Handling**:
   - **Clear**: Clears both the output and history.
   - **Backspace**: Deletes the last character in the output.
   - **Equals (`=`)**: Evaluates the entered expression and displays the result.
   - **Other Operators (+, -, *, /)**: Adds the selected operator to the history and clears the output for the next number input.

## Installation

1. **Download the Files**:
   - Clone or download the repository to your local machine:
     ```bash
     git clone https://github.com/your-username/simple-calculator.git
     ```

2. **Open the Project**:
   - Navigate to the project folder and open `index.html` in any modern web browser (Chrome, Firefox, Safari, etc.) to use the calculator.

3. **Customization**:
   - You can modify the appearance of the calculator by editing the `style.css` file.
   - To add more functionality (like scientific functions or other operations), you can extend the logic in the `script.js` file.


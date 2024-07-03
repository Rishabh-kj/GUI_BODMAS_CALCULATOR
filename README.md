# GUI_BODMAS_CALCULATOR
A simple **BODMAS (Bracket, Order, Division, Multiplication, Addition, Subtraction) calculator** implemented in Python using the Tkinter library for the **GUI (Graphical User Interface)**. This calculator supports basic arithmetic operations, exponentiation, and includes functionalities like clearing the input, backspacing, and displaying invalid input messages.

**Features: -**
- GUI: Built using Tkinter for a clean and user-friendly interface.
- BODMAS based Arithmetic Operations: Supports addition, subtraction, multiplication, division, and exponentiation.
- Input Handling: Handles user inputs through on-screen buttons and evaluates expressions.
- Error Handling: Displays a message for invalid input expressions.
- Clear and Backspace: Provides buttons to clear the entire input or delete the last character.
- Exit Button: Allows users to exit the application gracefully.

**Code Structure:**
The code consists of a create_window function which initializes the main window, sets up the input area, and defines all the buttons along with their functionalities.

**Main Components: -**
- Window and Frame Setup: Creates the main window and a frame with padding and background color.
- Input Area: A text entry widget to display and edit the mathematical expressions.
- Buttons: A set of buttons for digits (0-9), arithmetic operators (+, -, *, /), backspace, clear, equal, exponentiation, and exit.
- Functions:
  -> inputter(s): Inserts the string s at the end of the input area.
  -> backspacer(): Deletes the character before the cursor in the input area.
  -> clearer(): Clears the entire input area.
  -> equaler(): Evaluates the expression in the input area and displays the result or an error message.

**Example GUI Layout: -**

![image](https://github.com/Rishabh-kj/GUI_BODMAS_CALCULATOR/assets/132807853/9215a0ec-c98d-4b0a-86e7-d66681eb665b)


**Possible Future Enhancements: -**
- Extending Functionality: Support for more complex mathematical operations and functions can be added.
- Input Validation: Enhanced input validation can be incoporated to prevent invalid expressions from being entered.

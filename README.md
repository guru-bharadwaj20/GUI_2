# GUI_2
This Python program creates a simple calculator using Tkinter, allowing users to perform basic arithmetic operations. It features an interactive GUI with buttons for numbers, operators, and functionality to evaluate expressions.

Features
1. Basic Arithmetic Operations: Supports addition, subtraction, multiplication, division, and percentage calculations.
2. Parentheses Support: Allows users to group expressions using parentheses for proper order of operations.
3. Clear and Evaluate: Includes a "Clear" button to reset the input and an "=" button to evaluate the expression entered.
4. Responsive UI: The user interface is clean and responsive, with buttons for all necessary digits, operators, and functionality.
5. Decimal and Zero Support: Users can input decimals and zero values for more precise calculations.

Code Explanation
1. Tkinter Setup: The main window (root) is created using Tkinter, and its properties (size, title, color) are configured.
2. Button Layout: Buttons for digits, operations, and other functionalities are created and positioned using the place() method.
3. StringVar: The current equation is stored in a StringVar which is linked to an entry widget that updates dynamically as the user enters values.
4. Eval Function: The eval() function is used to evaluate the mathematical expression entered by the user. This is processed when the "=" button is clicked.

Limitations
1. Security Risk: The eval() function can be dangerous if used with untrusted input. In this case, it works because the input is strictly controlled through button clicks, but it is important to be cautious when using eval() in more general scenarios.
2. Basic Operations Only: This calculator supports only basic arithmetic operations and does not include more complex mathematical functions (like square roots, exponentiation, etc.)

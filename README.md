# python project  calculator

**Simple Arithmetic Calculator with Tkinter**

**Description**

This Python application uses the tkinter library to create a graphical user interface (GUI) calculator. The calculator allows users to perform basic arithmetic operations (addition, subtraction, multiplication, division) by entering two numbers and an operator.
Features
A GUI built with tkinter that is easy to use and interactive.

**Performs the following arithmetic operations:**
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Displays the result of the calculation in a label below the inputs.

**How It Works**
The calculator accepts three inputs:

First number: The first operand for the calculation.
Operator: The arithmetic operation to perform (+, -, *, /).
Second number: The second operand for the calculation.
After clicking the "Calculate" button, the result is displayed in a label.

**Installation and Usage**
**Requirements**
Python 3.x installed on your system.
The tkinter library (comes pre-installed with Python).
**Steps to Run the Application**__
**Clone this repository to your local machine:**
_git clone https://github.com/RosanaBlazheska/python-project--calculator.git_
_cd python-project--calculator_
**Run the Python script:**
python _calculator.py_
__A GUI window will appear with the following components:
Three input fields: To enter the first number, operator, and second number.
A "Calculate" button: To execute the calculation.
A label: Displays the result of the calculation.__

**Code Overview**
Entry Fields (entry1, entry2, entry3):
Accept the first number, operator, and second number, respectively.
Button (button):
Executes the calculate function, which performs the arithmetic operation.
Label (label):
Displays the result of the calculation.
Main Logic (calculate function):
Retrieves the inputs from the three entry fields.
Determines the operation based on the operator input.
Performs the calculation and updates the label with the result.
GUI Layout
The application window is 600x100 pixels in size with padding for spacing.
The layout includes:
Three horizontally aligned entry fields for input.
A button to trigger the calculation.
A label to display the result.
Notes
Ensure valid input is provided for all fields:
The first and third fields must contain numbers.
The second field must contain a valid operator (+, -, *, /).
Invalid inputs will result in the label displaying "Error".
Contributions
Contributions are welcome! Feel free to submit issues or pull requests.

LICENSE
This project is open-source and available under the MIT License.


Name: ASMILA D
Company: CODTECH IT SOLUTIONS
ID: :CT08DS7642
Domain: PYTHON PROGRAMMING
Duration: August 25th to September 25th 2024
Mentor: Neela Santhosh Kumar
Overview of the project
Project: To create a Python program that acts as a basic calculator.
Objective:
The goal of this project is to create a simple command-line calculator using Python. The calculator will allow users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The program will prompt the user to enter two numbers and select an operation, then display the result.

Features:
Basic Arithmetic Operations: The calculator can perform addition, subtraction, multiplication, and division.
User Input: The program takes input from the user for both the numbers and the choice of operation.
Error Handling: The calculator handles invalid inputs, such as non-numeric values and division by zero, gracefully.
Components
Function Definitions:

add(x, y): Returns the sum of x and y.
subtract(x, y): Returns the difference when y is subtracted from x.
multiply(x, y): Returns the product of x and y.
divide(x, y): Returns the quotient of x divided by y. Handles division by zero by returning an error message.
Main Function (main):

Greeting: Displays a welcome message.
Input Handling: Prompts the user to enter two numbers. Uses float to handle decimal numbers.
Operation Menu: Presents a menu of operations and prompts the user to select one.
Choice Handling: Calls the appropriate function based on the user’s choice and displays the result.
Error Handling: Uses a try block to catch ValueError exceptions for invalid numeric inputs and provides appropriate feedback.
Execution:

Script Entry Point: The if __name__ == "__main__": construct ensures that the main() function runs only when the script is executed directly, not when imported as a module.
Usage
Starting the Program:

The user runs the script from a command-line terminal.
The program prompts for two numbers and an operation choice.
Performing Calculations:

The user inputs the numbers and selects an operation by entering the corresponding number.
The program performs the calculation and prints the result.
Handling Errors:

If the user inputs non-numeric values or attempts to divide by zero, the program provides an error message instead of crashing.

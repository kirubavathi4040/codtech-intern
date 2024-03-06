# codtech-intern
Simple Calculator Documentation
Overview:
The Simple Calculator is a console-based Java program designed to perform basic mathematical operations such as addition, subtraction, multiplication, and division. Users can input two numbers and choose the operation they want to perform.

Features:
Supported Operations:

Addition
Subtraction
Multiplication
Division
User Interaction:

Users are prompted to choose an operation (1-4) from the menu.
They enter two numbers for the selected operation.
The program performs the calculation and displays the result.
Error Handling:

The program checks for division by zero and exits if the user attempts to divide by zero.
Invalid choices prompt an error message, and the program exits.
Usage:
Menu:

The user is presented with a menu displaying the supported operations.
They choose an operation by entering the corresponding number (1-4).
Input:

The user inputs two numbers when prompted.
For division, the program checks if the divisor is zero to avoid division by zero errors.
Calculation:

The program uses a switch-case statement to determine the selected operation.
The calculation is performed based on the chosen operation.
Output:

The result of the calculation is displayed to the user.
How to Run:
Compile:

Save the provided Java code in a file, e.g., SimpleCalculator.java.
Compile the code using a Java compiler: javac SimpleCalculator.java.
Run:

Run the compiled program: java SimpleCalculator.
Follow the on-screen prompts to perform calculations.
Example Usage:
markdown
Copy code
Simple Calculator
1. Addition
2. Subtraction
3. Multiplication
4. Division

Choose operation (1-4): 2
Enter first number: 8
Enter second number: 3
Result: 5.0





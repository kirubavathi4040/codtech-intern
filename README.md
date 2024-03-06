# codtech-intern


Simple Calculator Documentation
--------------------------------
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

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Student Grade Management System Documentation
-----------------------------------------------
Overview:
The Student Grade Management System is a console-based Java program designed to manage student information, calculate their overall percentage, and assign grades based on pre-defined criteria. It provides functionality to add, update, delete, and display student records.

Features:
Student Class:

Represents a student with attributes such as name, roll number, and subject marks.
Calculates overall percentage and assigns grades based on pre-defined criteria.
Main Program (GradeManagementSystem):

Manages the overall flow and user interaction through a menu-driven system.
Allows users to perform actions like adding, updating, deleting, and displaying student records.
Menu Options:

Add Student: Accepts student details and adds them to the list of students.
Update Student: Modifies the subject marks for an existing student.
Delete Student: Removes a student record based on their roll number.
Display Student Information: Shows details like name, roll number, subject marks, overall percentage, and grade.
Usage:
Main Menu:

Users are presented with a menu offering various options (1-5).
They choose an option to perform specific actions related to student records.
Add Student:

Users input the student's name, roll number, and subject marks.
The student is added to the list of students.
Update Student:

Users provide the roll number of the student to be updated.
New subject marks are entered, updating the student's record.
Delete Student:

Users enter the roll number of the student to be deleted.
The student record is removed from the list.
Display Student Information:

Users input the roll number to view detailed information about a specific student.
Exit:

Users can choose to exit the program.
Example Usage:
mathematica
Copy code
Student Grade Management System
1. Add Student
2. Update Student
3. Delete Student
4. Display Student Information
5. Exit
Enter your choice (1-5): 1

Enter student name: John Doe
Enter roll number: 101
Enter the number of subjects: 3
Enter marks for subject 1: 85
Enter marks for subject 2: 90
Enter marks for subject 3: 78
Student added successfully!

...

Student Grade Management System
1. Add Student
2. Update Student
3. Delete Student
4. Display Student Information
5. Exit
Enter your choice (1-5): 4

Enter the roll number of the student to display information: 101
Student Information:
Name: John Doe
Roll Number: 101
Subject Marks: [85.0, 90.0, 78.0]
Overall Percentage: 84.33333333333333
Grade: B
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

File Encryptor/Decryptor with GUI Documentation
------------------------------------------------
Overview:
The File Encryptor/Decryptor is a Java program with a graphical user interface (GUI) designed to encrypt and decrypt the contents of a text file using a simple Caesar cipher. Users can input the encryption/decryption key, load and save files, and perform encryption and decryption operations.

Features:
Caesar Cipher Encryption/Decryption:

Uses a basic Caesar cipher to shift letters in the alphabet based on the specified key.
Handles both encryption and decryption of the text file content.
Graphical User Interface (GUI):

Utilizes Java Swing to create an interactive GUI.
Allows users to input the encryption/decryption key, load and save text files, and perform encryption and decryption operations.
File Handling:

Users can load the content of a text file into the application.
The program supports saving the modified content back to a text file.
Usage:
GUI Interface:

The application provides a simple and intuitive graphical user interface.
Users can input the encryption/decryption key, load and save text files, and perform operations using buttons.
Encryption/Decryption:

Enter a numeric key in the "Encryption Key" field.
Use the "Encrypt" and "Decrypt" buttons to perform the respective operations on the loaded text.
Load and Save Files:

Click the "Load File" button to choose and load a text file into the application.
Click the "Save File" button to save the modified text back to a text file.
Bonus Features:
Integration of GUI:

The application integrates Java Swing for a graphical user interface.
Provides a more user-friendly experience compared to a console-based application.
Error Handling:

Basic error handling is implemented for file operations and key input.
Users are prompted with error messages for invalid operations or inputs.
Example Usage:
Encrypting Text:

Enter a numeric key in the "Encryption Key" field.
Click the "Encrypt" button to perform encryption on the loaded text.
Save the modified content using the "Save File" button.
Decrypting Text:

Enter the same numeric key used for encryption in the "Encryption Key" field.
Click the "Decrypt" button to reverse the encryption on the loaded text.
Save the modified content using the "Save File" button.
Load and Save Files:

Click the "Load File" button to choose and load a text file.
Make sure to save the modified content using the "Save File" button.

















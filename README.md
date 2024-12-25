NAME:KANDULA NAGA SURENDAR REDDY
COMPANY:CODETECH IT SOLUTIONS
ID:CT12DS2998
DOMAIN:PYTHON PROGRAMMING
DURATION:NOVEMBER 30th TO JANUARY 30th,2025
Project Overview:
The provided Python code implements a basic calculator that performs addition, subtraction, multiplication, and division 
operations. It uses a menu-driven interface to allow users to select the desired operation and input the necessary numbers.

Key Features:
Menu-driven interface: Users choose the operation by entering a number from 1 to 5.
Error handling: The code checks for division by zero and displays an appropriate error message.
Clear output: The result of the calculation is displayed in a user-friendly format.
Loop for multiple calculations: The calculator continues to operate until the user chooses to quit.


Summary:
The project successfully creates a functional calculator that can handle basic arithmetic operations.
It provides a user-friendly interface and incorporates error handling to enhance its reliability. 
The code is well-structured and easy to understand, making it a valuable resource for learning Python programming concepts.







NAME:KANDULA NAGA SURENDAR REDDY
COMPANY:CODETECH IT SOLUTIONS
ID:CT12DS2998
DOMAIN:PYTHON PROGRAMMING
DURATION:NOVEMBER 30th TO JANUARY 30th,2025
PROJET OVERVIEW:
This Python code defines a Student class to manage student information, including name, grades, and letter grades.  Here's a breakdown of the key aspects:

Class Definition (Student):

_init_(self, name): This method initializes a new student object. It takes a name argument and stores 
it in the self.name attribute. It also creates a dictionary named self.grades to hold the student's grades for different subjects.
add_grade(self, subject, grade): This method adds a grade for a specific subject. It takes subject (e.g., "Math") and 
grade (e.g., 85) as arguments and stores them in the self.grades dictionary with the subject as the key and the grade as the value.
calculate_average(self): This method calculates the student's overall grade average. It iterates through the self.grades dictionary,
sums all the grades, and divides by the total number of grades to get the average.
get_letter_grade(self): This method calls calculate_average and then converts the average into a letter grade based on a predefined 
scale (A >= 90, B >= 80, etc.).
display_grades(self): This method displays a formatted report for the student, including their name, a table showing subjects and grades, 
the calculated average grade, and the letter grade.
Main Script:

The script prompts the user for the student's name and creates a new Student object with that name.
It then enters a loop to collect subject and grade information. The loop continues until the user enters "quit" for the subject.
After the loop, the script calls the display_grades method of the student object to show all the entered information in a formatted way.
Summary:

This code provides a basic framework for managing student data. It allows for adding grades for different subjects, calculating the average grade,
converting it to a letter grade, and displaying all the information in a user-friendly report.

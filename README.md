1. Project Overview

The Student Grade Calculator is a Java-based console application designed to calculate a student's academic performance by accepting marks for multiple subjects, calculating total marks and average percentage, assigning a grade based on predefined criteria, and displaying the final result in a structured format.

The application demonstrates core Java programming concepts including variables, loops, arrays, arithmetic operations, conditional statements, input validation, methods, and object-oriented programming principles.

2. Project Objectives
Primary Objectives
Accept marks for multiple subjects.
Validate user input.
Calculate total marks obtained.
Calculate average percentage.
Determine grade based on percentage.
Display a formatted result card.
Secondary Objectives
Demonstrate Java programming fundamentals.
Create a reusable and maintainable code structure.
Improve understanding of arrays, loops, methods, and OOP concepts.
3. Functional Requirements
FR-1: Subject Input

The system shall allow the user to enter the number of subjects.

Acceptance Criteria
Number of subjects must be greater than zero.
User should be prompted until valid input is entered.
FR-2: Marks Entry

The system shall allow the user to enter marks for each subject.

Acceptance Criteria
Marks must be between 0 and 100.
Invalid marks should trigger an error message.
User must re-enter invalid marks.
FR-3: Total Marks Calculation

The system shall calculate the total marks obtained by the student.

Formula
Total Marks = Sum of all subject marks
FR-4: Average Percentage Calculation

The system shall calculate the average percentage.

Formula
Average Percentage = Total Marks / Number of Subjects
FR-5: Grade Assignment

The system shall assign a grade based on the average percentage.

Grade Criteria
Percentage	Grade
90 - 100	A+
80 - 89	A
70 - 79	B
60 - 69	C
50 - 59	D
Below 50	F
FR-6: Result Display

The system shall display:

Number of subjects
Marks entered
Total marks
Percentage
Grade
Pass/Fail Status
4. Non-Functional Requirements
Performance
Calculation should complete instantly.
Reliability
Invalid inputs should not crash the application.
Usability
Console prompts should be clear and easy to understand.
Maintainability
Logic should be divided into methods.
5. System Flow
Start
   |
Enter Number of Subjects
   |
Enter Marks for Each Subject
   |
Validate Input
   |
Calculate Total
   |
Calculate Percentage
   |
Assign Grade
   |
Display Result
   |
End
6. Technical Requirements
Programming Language

Java

Concepts Used
Variables
Arrays
Loops
Methods
Arithmetic Operations
Conditional Statements
Scanner Class
Object-Oriented Programming

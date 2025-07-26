Task 1 Calculator

The code snippet is a simple Python program that performs basic arithmetic operations—addition, subtraction, multiplication, and division—on two user-provided integers.
Purpose: Prompts the user to input the first number. The input() function: Reads input from the user as a string. The int() function: Converts the input string to an integer.
The result is stored in the variable a.Functions similarly to the first line, capturing and converting the second user input to an integer and storing it in variable b.
Add: Computes the sum of a and b.
Sub: Computes the difference (a minus b).
Multiply: Computes the product of the two numbers.
Divide: Computes the quotient of a divided by b.
Each result is stored in a corresponding variable. This print() function displays the results of the four operations, formatted for clarity.
Potential Enhancements
Error Handling: To prevent runtime errors such as division by zero, consider adding a try-except block.
Input Validation: Ensure the user inputs valid integers.
Formatting: For improved readability, floating-point results can be rounded.

Task 2 Welcome Full Name

This Python script prompts the user to input their first and last name, combines the inputs to form a full name, and then displays a personalized greeting message.
Purpose: Prompts the user to enter their first name. The input() function: Captures user input as a string. The str() constructor: Explicitly converts the input to a string 
(although it's redundant here, since input() already returns a string). The resulting string is stored in the variable a. Similar to the previous line, this captures the 
user's last name and stores it in the variable b. String concatenation: Combines the first name (a), a space (" "), and the last name (b) into a single string.
The result is stored in the variable full_name.Formatted string literal (f-string): Inserts the value of full_name directly into the string.
Output: Displays a personalized greeting that includes the user's full name.Input validation: You might check for empty strings or trim leading/trailing whitespace.
Title case formatting: Apply .title() to a and b for proper capitalization .Code readability: Variable names like first_name and last_name improve clarity over single 
letters (a, b).

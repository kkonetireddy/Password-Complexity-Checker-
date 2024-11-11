PRODIGY_CS_03
Password Strength Assessment Tool
Description
This tool assesses the strength of a password and provides feedback on how to improve it. It evaluates the password based on several criteria, including length, the presence of uppercase and lowercase letters, digits, and special characters.

Features
Checks password length and character diversity.
Provides a strength score from 0 to 10.
Offers feedback on how to improve password strength.
Requirements
C++ compiler (e.g., g++, clang++)
Standard C++ libraries
How to Compile
Save the code in a file named password_strength.cpp.
Open a terminal and navigate to the directory where the file is saved.
Compile the program using the following command:
g++ password_strength.cpp -o password_strength
How to Run
After compiling, you can run the program with:

./password_strength
Usage
The program prompts you to enter a password.
After entering the password, it will display the strength assessment along with a score.
It will also provide feedback on how to strengthen the password.
Example
Password Strength Assessment Tool
Enter your password: Example123!
Password Strength: Strong (Score: 8/10)

Feedback:
- Your password is strong!
Limitations
The assessment is based on specific criteria and may not cover all aspects of password security.
Passwords longer than the maximum allowed length are not assessed correctly.
License
This project is open-source and available for personal or educational use.

# Form-Validation-Console-Application
A console application in C++ using Repl.it to verify user input for an account creation form. The app checks the validity of name, CNP, phone number, and email address, displaying errors if data doesn't meet the required format.

## Description
This project aims to create a console application in C++ using Repl.it that verifies the data entered in a form used to create an account on an institution's website. The form includes the following fields:

- Full Name
- CNP (Personal Identification Number)
- Phone Number
- Email Address

The application will perform the following tasks:

### Data Input and Validation
1. The user will be prompted to enter the following information:
   - Full Name: The user's first name and last name (surname).
   - CNP: The user's 13-digit Personal Identification Number.
   - Phone Number: The user's 10-digit phone number.
   - Email Address: The user's email address.

2. The application will validate each input field to ensure that:
   - The "Full Name" field contains only letters and is in the correct format.
   - The "CNP" field has exactly 13 digits and starts with a valid code (1, 2, 5, or 6).
   - The "Phone Number" field has exactly 10 digits and contains only numbers.
   - The "Email Address" is in a valid format, containing '@' and at least one '.' after '@'.

### Output
1. If the entered data passes the required validations, the application will display the correct input data, including the user's date of birth (extracted from the CNP) in the format day, month, year.

2. If any of the input data fails the validation, the application will display an error message, specifying the validation issue for each field that didn't meet the required format.

## Getting Started
To run the project code please click the link below:

[Proiect integrator](https://replit.com/@palllaura/Proiect-integrator#main.cpp) / Repl.it

## Example screenshots:

Here are some example input data and their corresponding output from the program.
<br><br>
<img width="2048" alt="Screenshot 2022-07-04 at 19 51 16" src="https://github.com/laurapall/Form-Validation-Console-Application/assets/48211193/f34ccbe9-0506-4c8e-8167-3f564666edb1">

<br><br>

<img width="2048" alt="Screenshot 2022-07-04 at 19 51 38" src="https://github.com/laurapall/Form-Validation-Console-Application/assets/48211193/9c200a90-9857-4983-8bda-a609d5cfc663">

<br><br>

<img width="2048" alt="Screenshot 2022-07-04 at 19 51 55" src="https://github.com/laurapall/Form-Validation-Console-Application/assets/48211193/9b96ad10-9a93-41ac-9a53-d406fedfc86b">

<br><br>

## Contact
If you have any questions or suggestions, feel free to reach out to me at [flaurapall@gmail.com].

## Notes
In the code, "in-line" comments are used to explain various sections.

## Author
- [Pall Laura](https://github.com/laurapall)

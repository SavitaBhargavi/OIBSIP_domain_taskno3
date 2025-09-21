# password-generator
Random Password Generator (CLI): A Python command-line tool to generate secure, random passwords. Users can customize length, number of passwords, and include letters, digits, and symbols. It handles invalid inputs and can generate multiple passwords at once.
🎯 Objective

Create a secure and customizable password generator in Python to help users generate strong passwords quickly.

Basic Version: Generates random passwords using letters, digits, and symbols.

Advanced Version: Adds a GUI, multiple customization options, and clipboard copy functionality.

🛠️ Steps Performed
🔹 Basic Version

Defined character sets: letters, digits, symbols.

Collected user input for password length.

Generated a random password using Python’s random module.

Displayed the generated password in the console.

🔹 Advanced Version

Developed a Tkinter GUI for user-friendly interaction.

Added password length slider and checkboxes for letters, digits, and symbols.

Generated random passwords based on selected options.

Implemented clipboard copy using pyperclip.

Added warning messages if no options are selected or password is empty.

⚙️ Tools & Technologies Used

Python

Libraries:

tkinter – GUI interface

random – Password generation

string – Character sets for letters, digits, symbols

pyperclip – Copy password to clipboard

messagebox – Display warnings and information

✅ Outcome

Basic Version: Generates strong random passwords in the console.

Advanced Version: Provides a user-friendly GUI with options for customization and clipboard copy.

Improves password security and user convenience.


🚀 Future Enhancements

Add password strength evaluation to indicate weak/strong passwords.

Allow saving passwords securely in an encrypted local file.

Include predefined password patterns for specific use cases (e.g., alphanumeric only).

Enhance GUI with themes, buttons, and better layout.

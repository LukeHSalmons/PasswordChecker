# Password Checker

This is a simple password checker script that allows you to check if a password has been exposed in any data breaches. By leveraging the "Have I Been Pwned" API, the script securely compares the provided password against a database of breached passwords.

## Table of Contents
- [Usage](#usage)
- [Getting Started](#getting-started)
- [Credits](#credits)

## Usage

To check if your password has been exposed, follow these steps:

1. Ensure you have Python 3 installed on your machine.
2. Save your passwords in a text file named `info.txt`, with each password separated by a space.
3. Run the script using the following command:

   ```bash
   python password_checker.py
   ```

   The script will read the passwords from `info.txt` and check each one against the "Have I Been Pwned" API.

4. The script will display the results for each password:
   - If the password has been found in data breaches, it will display the number of times it has been exposed and recommend changing the password.
   - If the password has not been found in any breaches, it will indicate that the password is safe to use.

## Getting Started

To use this password checker script on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/LukeHSalmons/PasswordChecker.git
   ```

2. Make sure you have Python 3 installed on your machine.
3. Install the `requests` module by running the following command:

   ```bash
   pip install requests
   ```

4. Create a text file named `info.txt` and add the passwords you want to check, each separated by a space.
5. Open a terminal or command prompt and navigate to the project directory.
6. Run the script:

   ```bash
   python checkmypass.py
   ```

## Credits

This programme has been created by Luke Hunter-Salmons (Myself).

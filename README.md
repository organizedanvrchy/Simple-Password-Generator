# Simple Random Password Generator (CLI)

## Summary
This Python script is a simple password generator that creates a random password based on user-defined criteria. The user can specify the number of letters, numbers, and symbols they want in their password. The program then generates a password by randomly selecting characters from predefined lists of letters, numbers, and symbols. The final password is shuffled to ensure randomness and security.

## Features
- **Customizable Password Length**: The user can specify the number of letters, numbers, and symbols they want in their password.
- **Random Character Selection**: The program uses the `random` module to randomly select characters from predefined lists of letters, numbers, and symbols.
- **Password Shuffling**: The generated password is shuffled to ensure that the characters are randomly ordered, increasing the password's security.
- **User Input Handling**: The program prompts the user to input the desired number of letters, numbers, and symbols, and handles the input to generate the password accordingly.
- **Immutable String Handling**: The program converts the password string to a list for shuffling and then back to a string for the final output.

## How to Use
1. Run the script in a Python environment.
2. Enter the number of letters, numbers, and symbols you want in your password when prompted.
3. The program will generate a random password based on your input and display it.

## Requirements
- Python 3.x

## Running the Program
To run the program, simply execute the script in your Python environment:
```bash
python main.py
```

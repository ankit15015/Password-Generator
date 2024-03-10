# Password-Generator

Password Generator


This is a simple password generator program written in Python. It generates random passwords based on user-defined lengths and adds numbers and uppercase letters to increase complexity. Here's how to use it:

------------

How to Run



Clone this repository to your local machine.
Open a terminal or command prompt.
Navigate to the directory where the code is located.
Run the password_generator.py file using Python.


```bash
    python password_generator.py
```


-------------

Usage



When prompted, enter the number of passwords you want to generate.
Enter the length for each password. (Note: The minimum length should be 3 characters.)
The program will generate and display the passwords.

-----------


Code Structure



The code consists of a main function main() which handles user input and password generation. It utilizes three helper functions:

generatePassword(pwlength): Generates random passwords based on user-defined lengths.
replaceWithNumber(pword): Replaces random characters in the password with numbers.
replaceWithUppercaseLetter(pword): Replaces random characters in the password with uppercase letters.



---------------
Sample Output


Below is a sample output of the program:

```bash

How many passwords do you want to generate? 3
Generating 3 passwords
Minimum length of password should be 3
Enter the length of Password #1: 8
Enter the length of Password #2: 6
Enter the length of Password #3: 5
Password #1: qr3wR8o5
Password #2: wu1gIy
Password #3: ce3rN

```

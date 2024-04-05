# Random-Password
This Python script generates a random password of a specified length.

generate_password(length): This function takes an integer length as input and returns a randomly generated password of that length. It uses the string module to get all possible characters (letters, digits, and punctuation marks), and then it randomly selects characters from this set to construct the password.

if __name__ == "__main__":: This block of code ensures that the following code is only executed if the script is run directly (not imported as a module).

password_length = int(input("Enter the length of the password: ")): This line prompts the user to enter the desired length of the password and converts the input to an integer.

password = generate_password(password_length): This line calls the generate_password function with the user-provided length and stores the generated password in the variable password.

print("Generated password:", password): This line prints the generated password to the console.

When you run this script, it will ask you to enter the desired length of the password, and then it will generate and print a random password of that length.

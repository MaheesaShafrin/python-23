# python-23
Write a Python Program to Find ASCII value of a character.
c = input("Enter a character: ")
if len(c) != 1:
    print("Please enter exactly one character.")
else:
    print("The ASCII value of '" + c + "' is", ord(c))


Output
Enter a character: a
The ASCII value of 'a' is 97

# Calculator
## Calculator Programme - Utilising Defensive Programming

## Project Details:

### Description
This was assigned as part of the HyperionDev Software Engineering Bootcamp that I am enrolled in. 

The purpose of this assignment was to demonstrate my understanding of defensive programming techniques and accounting for user inputs that could cause the programme to crash.



### Functionality
* The code begins by opening a new or cleared equations.txt file.

* User is prompted to input whether they would like to enter a new equation, see the equations from a text file or end the programme. 

* Option a - requests 2 numbers and the mathmatical operator. Loops are in place to prompt for valid integer inputs for the 2 numbers. 

For the operator, a counted loop is used to prompt user to input a valid operator symbol. A try-except-else block is used to avoid user receiving a ZeroDivisionError.

Once the calculation is validated, it is written to the equations.txt file.

* Option b - The code requests the file name from the user and a try statement is used to confirm the inputted file name can be located. 

the file data is read into the programme and displayed to the user.

* Option c - The main programme loop is broken and the user exits.


### How can I use it?
* You can clone the repository with the programme to a local repository on your computer so you can run the programme.

If you need help, please refer to the help page from github:

https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository

With this being a programme written with Python, you will need to download the Python interpreter programme onto your operating system (os) so you can view and run the code.

### Contributors
* This programme was created as a solo project to fulfill the sofware engineering bootcamp requirements. 


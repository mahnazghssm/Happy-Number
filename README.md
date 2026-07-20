# Happy number

This project implements a function to determine if a number is a happy number.

A happy number is defined as a number that, starting with any positive integer, can be replaced by the sum of the squares of its digits. This process is repeated until the number equals 1 (at which point it is considered a happy number) or it enters a loop that does not include 1 (in which case it is not a happy number).

For example:

- 19 is a happy number:
```
1^2 + 9^2 = 82  
8^2 + 2^2 = 68 
6^2 + 8^2 = 100 
1^2 + 0^2 + 0^2 = 1
```
- 2 is not a happy number as it enters a cycle that doesn’t include 1.

## project structure

```
Happy_numbers/
|
|- Run.py
|
|-README.md
```

Run.py:
This file contains the implementation of the is_happy function and some example test cases to verify its functionality.

README.md:
This file provides an overview of the project, its structure, and instructions on how to run it.

## requirements
This project is implemented in Python. To run the code, you’ll need to have Python installed on your system. There are no external dependencies for this project, so you can run it with a standard Python installation.

You can download and install Python from the official website: https://www.python.org/downloads/.

## how to run
1. lone the Repository: Start by cloning the repository or downloading the project files to your local machine.

```
git clone <repository-url>
cd Happy_numbers
```

2. Run the Script: Execute the Run.py file using the Python interpreter.
```
python Run.py
```

If the script runs successfully, and the test cases in the __main__ section pass, there will be no output, indicating that the function works correctly.

3.	Test with Custom Inputs: You can also modify the Run.py file to test the is_happy function with different numbers.


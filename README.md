# Elementary-Calculator-
Python Project - 03

# Python program to create a simple calculator

# 1. Functions for operations
# 2. User input
# 3. print result


" Step 1 - Create Functions "

# Function to add two numbers
def add(num1, num2):
    return num1 + num2


# Function to substract two numbers
def sub(num1, num2):
    return num1 - num2


# Function to multiply two numbers
def multiply(num1, num2):
    return num1 * num2


# Function to divide two numbers
def divide(num1, num2):
    return num1 / num2


# Function to average two numbers
def avg(num1, num2):
    return (num1 + num2)/2


" Step 2 - User Input "
print("Please select a operation:\n " \
      "1. Addition\n" \
      "2. Subtraction\n" \
      "3. Multiplication\n" \
      "4. Division\n" \
      "5. Average\n")

select = int(input("Select a operation from 1,2,3,4,5: "))

number1 = int(input("Enter the first number: "))
number2 = int(input("Enter the second number: "))

"Step 3 - Print the result of the operation "
if select == 1:
    print("Sum of two numbers is: " , \
           add(number1, number2))

elif select == 2:
    print("Subtraction of two numbers is: " , \
           sub(number1, number2))

elif select == 3:
    print("Multiplication of two numbers is: " , \
           multiply(number1, number2))

elif select == 4:
    print("Division of two numbers is: " , \
           divide(number1, number2))

elif select == 5:
    print("Average of two numbers is: " , \
           avg(number1, number2))

else:
    print("Invalid operation! Pls select again!")

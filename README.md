# Learning Python BAsics Once AGAIN!!!! Starting From the variables

# Chapter1

# Variables:
Variables are used to store values. Each variable has a name and a value.
The variable name can consist of nmaes, numbers and _(underscore)

These are all valid valiables in programming:
- name = 'Ritvik' (string)
- Progress_id = 1 (interger)
- verified_programmer = True (Bool value)

# Data Types: 

**Integer:** An *int*, is a whole number. It has no decimal point and contains number 0, positive and negative counting numbers. If we were counting the number of people on the bus or the number of jellybeans in a jar, we would use an integer.

For Example: 

    year = 2023
    age = 32
# Float:

A **Floating-Point** number or a *float* is decimal number. It can be used to represent fractions or precise measurements. If we were measuring the length and width of the couch, calculating the test score percentage, or storing a cricket player's batting avg we would use a *float* instead of *int*

for Example:

    pi = 3.14159
    meal_cost = 12.99

# String:

A **String** or *str* is used for storing text. Strings are wrapped in double quotes *""* or single quotes *''*.

For Example:

    message = 'Good Morning'
    username = "@Rizz"

# Boolean:

A boolean data type, or bool, stores a value that can be either *true* or *false*. In python .it's capitalized ***True*** or ***False*** 

For example:

      late_to_class = False
      Cranky = True


# Chapter 2:

# Operators: 
Python has the following arithematic operators:
- '+' --> Addition
- '-' --> Subtraction
- '*' --> Multiplication
- '/' --> Division

For Example: 

        score1 = 0  # Score is 0
        score2 = 4 + 3  # Score is 7
        score3 = 5 - 2  # Score is 3
        score4 = 5 * 2  # Score is 10
        Score5 = 4/2  # Score is 2

**This code calculates a 20% tip by calculating the total and then multiplying bya float(decimal number):**

        Pizza = 2.99
        coke = 1.77

        total = pizza + coke

        tip = total * 0.2

        print(tip)
*Another way to write this using paraentheses to calculate the total and the tip in one line:*
tip = (coke + pizza) * 0.2

In python, *Parentheses* ahve the highest order just like ***PEMDAS***

**Question1:**

*Create a temperature.py progarmme that converts a number from Farenheit to Celcius

Use the following formula and write it in python:

**celcius = (farenheit - 32)/1.8**

Answer: 

        Farenheit = int(input("Enter the Temperature in Farenheit"))
        farenheit_to_celcius = (Farenheit - 32)/ 1.8
        
        print(f'The Converted Temperature from ferenheit to celcius is: {farenheit_to_celcius}')
        


    





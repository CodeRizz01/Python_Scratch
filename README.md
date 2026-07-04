# Learning Python Basics Once AGAIN!!!! Starting From the variables

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
        
# Modulo
Another operator that often trips people is the modulo operator. 

The *%* **Modulo** opertor doesn't give you the result of a division -it gives you the *remainder*

For Example:

        score1 = 5 % 3    # Score is 2
        score2 = 5 % 2    # Score is 1
        Score3 = 5 % 1    # Score is 0

# Exponents:

In written math, we might see an exponent as a superscript number(like above), but typing superscript isn't always easy on modern keyboards. Since exponentiation is super similar to multiplication, Python uses the notation **

For Example: 
 
    score1 = 2 ** 2   # Score is 4
    score2 = 2 ** 3   # Score is 8
    score3 = 4 ** 2   # Score is 16

**Question 2:**

The Body MAss Index (BMI) is used by health and nutrition professionals to qiuckly estimate body fat in certain populations.

The fomula is simple: Take an individuals's weight(mass) in kg and divinding it by their height in mtrs, squared.

    bmi = mass/height ** 2

So. now Create a bmi.py program that calculates your own BMI

Answer:

    Weight = int(input("Enter your weight: "))
    Height = int(input("Enter your height: "))

    bmi = Weight/(height) ** 2

    print(f'The BMI of the person is {bmi * 10 ** 4} ')

#User Input:

Python uses the input() function to get user input:

    username = input("Enter you name: ")
    print(username)

The output will say "Enetr your name: ", and the user can type in something, hit *enter* and whatever the user typed gets stored into the *username* variable

So, here, suppose the user types in their name and pressed *enter*, it will output their name.


# int()

The user input is stored as a text string, which is okay for now.

in that case, we would need to wrap an *int()* around the *input()* t oconvert the text string into a number:

    # Input:
    age = int(input("What's i0s your age ? "))
    print(age)

    # Output:
    Enter your age: 50
    50
Now when the user types 50 and presses Enter, the *age* variable will ne an interger 50, not a text string "50"

**Question 3**

Pythogorean Theoremis the relation between the three sides of a right angled triable. 

The Equation looks like  <img width="172" height="34" alt="image" src="https://github.com/user-attachments/assets/bd219c7a-2336-40bf-b40c-38cd77d30124" />

- The *a* is the length of a short side
- The *b* is the length of another shorter side
- The *c* is the length of the hypotenuse.

The hypotenuse is the longest side of the right triangle.

Create a **hypotenuse.py** program that asks the user for two nummber *a* and *b*, and the calculates the hypotenuse *c*. 

Answer: 

        a = int(input("enter the length of side a: "))
        b = int(input("Enter the length of side b: "))

        c = ((a**2) + (b**2)) ** 1/2

        print("The answer is: ", c)


# Control Flow in Python:









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

**If -Else Conditional Statements:**

It directs a computer program to evaluate a specific condition and execute one block of code if the condition is true, or an alternative block of code if it is false.

Think of it like a real-world decision:

- if it is raining, bring an umbrella.
- else (otherwise), wear sunglasses.


Based on this, the conditional statements are further classified into following types

- if
- else
- if--else--elif
- nested if--else--elif

*An if - else statement evaluvates like this:*

**If the expression evaluvates true:**
Execute the block of code inside if statement. AFter execution return to the code out of the if - else block.

**if the expression evaluvates False:**
Executes the block of code inside else statement. After execution return to the code out of h=the if - else block.

For example:

        a = int(input("Enter your age: "))
        print("Your age is:", a)

        # Conditional operators ---> These are the operator used by if statements to check the conditions
        # <, >, >=, <=, ==< !=
        #print(a > 18)
        # print(a <= 18)
        # print(a == 18)
        # print(a != 18)

        if(a > 18):
            print("You can drive")
        else: 
            print("You can't drive")

Output:

    Enter your age: 20
    Your aae is: 20

    False
    True
    True
    False

    You can drive

    Enter your age: 18
    your age is: 18

    False
    True
    True
    False

**elif - Statement:**

Sometimes, the programmer may want to evaluvate more than one condition, this can be done using an elif statement.

**Working of an elif statement:**

Execute the block of code inside if statement if the initial expression evaluvates to True. After execution return to the code out of the if block.

Execute the block of code inside the first elif statement if the expression inside it evaluvates True. After execution return to the code out of the if block.

Execute the block of code inside the second elif statement if the statement expression inside it evaluvates True. After execution return to the code out of the block.

Execute the block of code inside else statement if none of the expression evaluavtes to True. After execution return to the code out of the if block.

Example: 

    num = 0
    if (num < 0):
        print("Number is negative: ")
    elif (num == 0):
        print("Number is Zero")
    else: 
        print("Number is positive.")

Output:

    Number is Zero.

**Nested if-else-elif statement:**

We can use if, if-else, elif statement inside other if statement as well

num = 18
if (num < 0):
    print("Number is negative")
elif (num > 0):
    if (num <= 10):
        print("Number is between 1-10")
    elif (num > 10 and num <= 20):
        print("Number is between 11 - 20")
    else: 
        print("Number is greater than 20")
else: 
    print("Number is zero")


Output:

    Number is between 11-20

# Loops
sometimes a programmer wants to execute a group of statement a certain number of times. This can be done using loops. 
Based on this loops are further classified into following types: for loop, while loop, nested loops.

**for loop**

for loop can iterate over a sequence of iterable objects in python. Iterationg over a sequence is nothing but iterating over strings, lists, tuples, sets, and dictionaries.

Example: Iterating overa string:

    name = 'Rizz'
    for i in name:
        print(i, end=", ")

output:

    R,i,z,z


*Example: iterating over a list:*

    colors = ['Red', 'Green', 'Blue', 'Yellow']
    for color in colors:
        print(color, end", ")

Output:

    Red, Green, Blue, yellow


*Example_2*

    colors = ["Red", "Green", "Blue", "Yellow"]
    for color in colors:
        print(color)

    for i in color:
        print(i)

Output:

    Red
    R
    e
    d
    Green
    G
    r
    e
    e
    n
    Blue
    B
    l
    u
    e
    Yellow
    Y
    e
    l
    l
    o
    w

Similarly, we acn use loops for lists, sets and dictionaries.

**range():**
what if we do not want to iterate over a sequence ?
what if we want to use loo for a specific number of times?

Here, we can use the range() function.

Example:

    for i in range(5):
        print(i)

Output:

    0
    1
    2
    3
    4
    


Example_2:

    for j in range(1, 5)
        print(j)

Output:

    1
    2
    3
    4
Here, In this example it will print the range of number *1 to 4*, it will not print *5* as *5* is the exclusive number. that it is not included.

So if you want to print then the range should be *1,6* so it will print the number from *1 to 5*

Example_3:

    for k in range(1, 1, 10)
        print(k)

Output:

    1
    3
    5
    7
    9

Here, In this case it will print leaving one number after another, which is known as *step value*.

**While Loop:**

While loop is used to execute a block of statement repeatdly until a given condition is satisfied. When the condition becomes false, the line immediatly after the loop in the program is executed.

Here, the condition for while will be True as long as the counter variable(count) is less than 3.

Example:

        count = 0
        while count < 3:
            count = count + 1
            print("Hello World")
Output:

    Hello World
    Hello World
    Hello World

**Parameters:**
- **condition** --> A boolean expression. If it evaluvates to True, code inside the loop will execute.
- **statement(s)** --> that will be executed during each iteration of the loop.

**Infinite While Loop**
An infinite loop is a loop that keeps running continuously because it's condition always remains True. Such loops do not stop on their own and continue executing until the program is manually terminated.

Example:

    age = 18
    while age > 18:
        print("Infinite Loop")
Output:

    Infinite Loop
    Infinite Loop
    .
    .
    .

here, teh condition *age > 18*, is True because the value of age never chnages inside the loop. Therefore the loop runs infinitely.

**Using with continue statement:**
Continue statement is used to skip the current iteration of the loop and move directly to the next iteration.

Example:

    i = 0
    a = 'Hello World'

    while i < len(a):
        if a[i] == 'e' or a[i] == 'l':
            i = i + 1
            continue
        print(a[i])
        i = i + 1

Output:

    H
    l
    l
    o

    W
    o
    r
    d

Here, whenever the character is 'e' or 'l', the loop skips printing it continue with the next character.

**Using with break statement:**

*Break statement* is used to immediately terminate teh loop when a specific condition becomes True.

Example: 

    i = 0
    a = 'Hello World'

    while i < len(a):
        if a[i] == 'e' or a[i] == 'l':
            i = i + 1
            break
        print(a[i])
        i = i + 1

Output:

    H
Here, the loop stops as soon as it encounters the character 'e' or 's'.

**Using with pass statement:**

*pass statement* is a null statment. It does nothing when executed and is mainly used as placeholder for future code.

Example:
    
    a = 'Hello World'
    i = 0
    while i < len(a):
        i = i + 1
        pass

    print('Value of i: ', i)

Output:

    Value of i : 11

Here, the loop runs through all character of the string, but the pass statement performs no action inside the loop body.

**Using with else:**
esle block a while loop executes only when the loop finishes normally without encountering a break statement. In forst eg, loop completes all iterations, so the else block executes. In second example, loop stops because of break, so the else block is skipped.

Example: 

    i = 0
    while i < 4:
        i = i + 1
        print(i)

    else: 
        print("No break\n")

    i = 0
    while i < 4:
        i = i + 1
        print(i)
        break
    else: 
        print(no Break)
Output:

    1
    2
    3
    4
    No Break

    1


    


        










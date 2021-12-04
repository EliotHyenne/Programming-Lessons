# Python 1 (variables, print, if, elif, else, input):

## **Variables**

```python
"""
Syntax:

    variableName = <value>

Description: Variables are containers for storing data values.
"""

# Example:

# Integer
daysUntilChristmas = 21

# Float
highScore = 42.7

# String
myName = "Shun"

# Boolean (True or False)
todayIsRaining = True
```

## **Print**

```python
"""
Syntax:

    print(<insert something here>)

Description: Print whatever is in the parentheses in the terminal.
"""

# Example:

print("Antony sucks!") # Output: Antony sucks!
print(10) # Output: 10
print("I am " + 23 + " years old") # Output: I am 23 years old
print("I am", 23, "years old") # Output: I am 23 years old

# Printing variables
highScore = 42.7
print(highScore) # Output: 42.7
print("My high-score is", highScore) # Output: My high-score is 42.7
```

## **If/Elif/Else:**

```python
"""
Syntax:

    if <condition>:
        <body of if>
    elif <condition>:
        <body of elif>
    else:
        <body of else

Description: A way for the program to execute different statements depending on conditions
"""

# Example:

a = 20
b = 50

# Greater than/Smaller than
if a > b:
   print("a is greater than b")
else:
   print("a is smaller or equal to b")

if a < b:
   print("a is smaller than b")
else:
   print("a is bigger or equal to b")

# Equal to/Not equal to
if a == b:
   print("a is equal to b")
else:
   print("a is not equal to b")

if a != b:
   print("a is not equal to b")
else:
   print("a is equal to b")

# Everything put together:
if a > b:
   print("a is bigger than b")
elif a < b:
   print("a is smaller than b")
else:
   print("a is equal to b")

# NB: You also have >= and <=
```

## **Input**

```python
"""
Syntax:

    variable = input(<insert prompt here>)

Description: Get input from the user in console and assign it to a variable
"""

# Example:

name = input("What is your name? ")
print("Nice to meet you " + name)
```

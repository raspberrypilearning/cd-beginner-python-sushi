## Keep asking

You can ask users to pick a number now, check if it's the right size and, and if it isn't, tell them it's not. What if you wanted to keep your program going until you got an answer that was the right size?

You need a way to ask your question over and over until you get the right kind of answer. The way to do this in computer programming is called a **loop**. You're going to use one called the `while` loop.

A `while` loop is a bit like an `if` statement: it has code inside it that only runs if the condition in brackets is true. The difference is that a `while` loop runs over and over, until its condition is false. You have to make sure that there always is a way out of your `while` loop, otherwise it will run forever! It looks like this:

```python
while(my_number < 100):
    my_number = input("Hello "+name+" please pick a number that's bigger than 100")
    my_number = int(my_number)
```

--- task --- Now add a `while` loop to your program, to keep asking users for a number until they give that's lareger than 100.

```python
name = input("What is your name?")
my_number = 0

# Loop as long as "my_number" is less than 100
while(my_number < 100):
    # Ask users for a number
    my_number = input("Hello "+name+" please pick a number that's bigger than 100")
    # Convert users' answer from a string to an integer
    my_number = int(my_number)
    print("Your number is "+str(my_number))
    # Check if the number is bigger than 100
    if(my_number > 100):
        print("That's a big number!").
    elif(my_number > 90):
        print("Almost there! Try again!")
    else:
        print("That number is too small! Please try again!")
    # If my_number is smaller than 100 at this point, loop again
```
--- /task ---

--- collapse ---
---
title: What's that extra text – is it part of the code?
---

The extra lines of text that start with a `#` symbol are **commments**.

In most programming languages, you can write comments in your code. These are notes about what the code does that the computer will ignore. You can write them for yourself as reminders, or for other programmers who want to use your code. In Python, comments start with `#` and last to the end of the line.

--- /collapse ---

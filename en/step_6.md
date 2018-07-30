## Check more than one thing

What if you want to check if the user's number is big enough, and let them know if it's not? Let's try to check whether it's bigger than 100. Then, either congratulate the user on giving a number that's big enough, or tell them where they didn't go big enough. 

+ Try this:

```python
name = input("What is your name?")
my_number = input("Hello "+name+" please pick a number that's bigger than 100")
my_number = int(my_number)
print("Your number is "+str(my_number))

if(my_number > 100):
    print("That's a big number!")
else:
    print("That number is too small!")
```

  The code inside the `else` statement runs whenever the condition in the bracket of the `if` statement isn't true.
  
### More conditions

What if you want to tell the user when they're close, for example if they've picked a number over `90`?

Then you can use an `elif` statement! That name is the words 'else' and 'if' stuck together. The code inside an `elif` statements runs only when the condition in the `if` statement is not true **and** the condition in the `elif` statement's brackets is true. 

+ So here's what you add to get the program to tell the user they're close:

```python
elif(my_number > 90):
    print("Almost there!")
```

And here's what it looks like with the rest of the program. Notice that the `elif` statements has to come between the `if` and the `else` statements.

```python
name = input("What is your name?")
my_number = input("Hello "+name+" please pick a number that's bigger than 100")
my_number = int(my_number)
print("Your number is "+str(my_number))

if(my_number > 100):
    print("That's a big number!")
elif(my_number > 90):
    print("Almost there!")
else:
    print("That number is too small!")
```

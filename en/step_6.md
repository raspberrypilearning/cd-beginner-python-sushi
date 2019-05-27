## Check more than one thing

What if you want to check if the user's number is big enough, and let them know if it's not? 

You can combine conditions by using `and` and `or`. So you could write code like this:
```python
if(my_number >= 20 and my_number < 30):
    print("That number is in the twenties!")
```
Or, for example:
```python
if(food == "Cake" or food == "Chocolate" or food == "Pie"):
    print("Sounds tasty!")
```

--- task ---
Check whether the user's number is bigger than 100. Then, either congratulate the user on giving a number that's big enough, or tell them where they didn't pick a number big enough. 

Try this:

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
--- /task ---

The code inside the `else` statement runs whenever the condition in the bracket of the `if` statement _isn't_ true.
  
### More conditions

What if you want to tell the user when they're close, for example if they've picked a number over `90`?

Then you can use an `elif` statement! That name is the words 'else' and 'if' stuck together. The code inside an `elif` statements runs only when the condition in the `if` statement _is not_ true **and** the condition in the `elif` statement's brackets _is_ true. 

Here's what you add to get the program to tell the user they're close:

```python
elif(my_number > 90):
    print("Almost there!")
```

--- task ---
Now add those lines into the rest of your program. Notice that the `elif` statements has to come between the `if` and the `else` statements.

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
--- /task ---

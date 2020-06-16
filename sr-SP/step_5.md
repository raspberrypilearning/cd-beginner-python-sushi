## Compare and check things

You can ask Python to compare one number to another number. This can be really handy for writing games (e.g. do players have as much money as this costume costs?).

You do this using special symbols:
* `a > b` checks whether `a` is bigger than `b`
* `a < b` checks whether `a` is smaller than `b`
* `a == b` checks whether `a` is the same as `b`
* `a != b` checks whether `a` is not the same as `b`
* `a >= b` checks whether `a` is bigger than, or the same size as, `b`
* `a <= b` checks whether `a` is smaller than, or the same size as, `b`

--- collapse ---
---
title: Why are there two equals signs together?
---

The two equal signs `==` are used to **compare** variables, because the single equal sign is already used to **assign** values to variables.

--- /collapse ---

You can use these comparisons to create `if` statements: code that should only run _if_ whatever is in the brackets (the **condition**) is true. Here, the `print` statement inside the `if` statement will only run if the value of `my_number` is larger than `100`;

```python
if(my_number > 100):
    print("That's a big number!")
```

#### Indentation
Notice that the `print` inside the `if` statement is **indented**. That means that four spaces have been put before it.

Python needs these spaces to understand your program!

Now, put that little bit of code together with your program from the last card.

--- task ---

Change the program so it looks like this:

```python
name = input("What is your name?")
my_number = input("Hello "+name+" please pick a number")
my_number = int(my_number)
print("Your number is "+str(my_number))

if(my_number > 100):
    print("That's a big number!")
```

--- /task ---

--- task ---

Now run it and try entering different numbers above and below 100 to see what happens. What would happen if you entered 100 exactly?

--- /task ---

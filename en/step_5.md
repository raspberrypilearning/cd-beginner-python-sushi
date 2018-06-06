## Comparison & if statements

You can ask Python to compare one number to another number. This can be really handy (does the player have as much money as those pants cost?). 

You do this using special symbols:
* `a > b` asks if `a` is bigger than `b`
* `a < b` asks if `a` is smaller than `b`
* `a == b` asks if `a` is the same as `b`
* `a != b` asks if `a` is not the same size as `b`
* `a >= b` asks if `a` is bigger than, or the same size as `b`
* `a <= b` asks if `a` is smaller than, or the same size as `b`  

--- collapse ---
---
title: Why is there two equals signs together?
---

The double-equals `==` is used to **compare** variables, because the single equals is already used **assign** values to them.

--- /collapse ---

You use these comparisons is inside `if` statements: code that should only run if a condition (in the brackets) is true. In this case, **printing** some text.

```python
if(my_number > 100):
    print("That's a big number!")
```

**Indentation**
The `print` is **indented**. That means that four spaces have been put before it. Python needs these spaces to understand your program.

+ Now, put that little bit of code together with your program from the last card. Change the program so it looks like this:
    
```python
name = input("What is your name?")
my_number = input("Hello "+name+" please pick a number")
my_number = int(my_number)
print("Your number is "+str(my_number))

if(my_number > 100):
    print("That's a big number!")
```

+ Now run it and try entering different numbers, above and below 100 to see what happens. What would happen if you entered 100 exactly?

You can also combine conditions, using `and` and `or`. So this let's you write code like:
```python
if(my_number >= 20 and my_number < 30):
    print("That number is in the twenties!")
```
Or, for example:
```python
if(food == "Cake" or food == "Chocolate" or food == "Pie"):
    print("Sounds tasty!")
```

+ Try changing your code to check if the number is in the thirties.

--- hints ---

--- hint ---

A number is in the thirties if it is greater than or equal to thirty, **and** less than forty.

--- /hint ---
--- hint ---

You can check this in your if statement by using an `and` to combine the two conditions: `(my_number >= 30 and my_number < 40)`.

--- /hint ---
--- hint ---

Your code should look like this:

```python
if(my_number >= 30 and my_number < 40):
    print("That number is in the thirties!")
```

--- /hint ---

--- /hints ---

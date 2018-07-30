## Talking to the user

Getting the computer to stick your name on the end of `"Hello "` is nice, but why not just write `"Hello [my name]"`? Because you don't have to know what's going to be stored in a **variable** when you write the program. You can even ask the user of the program to tell you what to put into it. 

+ Update your Python program so that it asks the user for the text to put in the variable:
  
  ```python
  name = input("What is your name?")
  print("Hello "+name)
  print("The Code, it's calling to you. Just let it in.")
  ```

+ Try running it. You'll need to press the <kbd>Enter</kbd> key once you've typed in your name.

+ Now, try collecting a number from your user by changing your code to look like this:

```python
name = input("What is your name?")
my_number = input("Hello "+name+", please pick a number")
print("Your number is "+my_number)
```
   Notice that you can use the `+` on both sides of a variable!

+ Run this program, answer its questions, and watch what happens.

What if you want to add another number to the number stored in your new variable?

+ Add a line to your program that will add `1` to the `my_number` variable:

```python
name = input("What is your name?")
my_number = input("Hello "+name+" please pick a number")
my_number = int(my_number) + 1
print("Your number is "+str(my_number))
```

--- collapse ---
---
title: How does the new code work?
---

You've just taken a value from a variable, changed it, and stored it back in the same variable — all on the same line!

Now, why does the code have `int()` and `str()` around `my_number`?

It's because Python makes a difference between the number '1' it uses for maths and the number '1' it writes in a sentence. Putting `int( )` around a variable tells it to treat it as an **integer** (a maths number), and putting `str( )` around it tells it to treat it as a text **string**.  

**Integers** and **strings** are variable **types**, and certain pieces of code (like `+` and `print`) only work if the variables you give them are the right type.

--- /collapse ---

### Maths in Python

You've seen how to add here, but you can also:
* Subtract using `-`
* Multiply using `*`
* Divide using `/`

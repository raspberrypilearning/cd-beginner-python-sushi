## Your first Python program

Time for your first bit of Python. You're going to get the computer to say hello to everyone. 

+ Type this into your code file:

```python
print("Hello everyone")
```

+ Run this code and see what happens!  

+ Try changing what’s inside the `"` symbols, maybe by adding your name, and running it again.

+ Now add another line: Try making your code look like this:

```python
print("Hello everyone")
print("The Code, it's calling to you. Just let it in.")
```

+ Run it again. See how the text (called a **string**) from the second `print` is on a new line? This is because the instruction the computer gets when you tell it to `print` is:
     1. Read the code in the brackets and figure out the result
     2. Once you’ve figured out what it says, `print` that out on the screen.
     3. Put an invisible “start a new line” instruction at the end.

Why does the computer need to figure out what the code in those brackets says? It's because the computer can put that **string** together from parts you give it.  

+ Try it! Use this code, but put your name in where it says "my name" (keep the `"` characters though!):

```python
name = "my name"
print("Hello "+name)
print("The Code, it's calling to you. Just let it in.")
```

--- collapse ---
---
title: The space after "Hello"
---

You have to include a space before the variable or you'll just get "Hellomy name"! Python doesn't know what English looks like!

--- /collapse ---

--- collapse ---
---
title: How does the new code work?
---

You made a **variable**, called `name`. This is like a box inside the computer, with a label on it. You can put anything you want in it. Then, you can use the label to get Python to go fetch the thing that’s in the box and use it in your code. 

So first, you created the `name` variable and stored `"[my name]"` in it.

On the next line, you used the variable to stick that name into your greeting, by using the `+` symbol to attach it to the end of the **string**.

--- /collapse ---

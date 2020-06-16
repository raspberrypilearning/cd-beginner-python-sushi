## Your first Python program

Time for your first bit of Python. You're going to get the computer to say hello to everyone.

--- task --- Type this into Trinket:

```python
print("Hello everyone")
```
--- /task ---

--- task --- Run the code and see what happens! --- /task ---

--- task --- Try changing what’s inside the `"` symbols, maybe by adding your name, and running it again. --- /task ---

--- task --- Now add another line, below the existing one:

```python
print("Hello everyone")
print("The Code, it's calling to you. Just let it in.")
```

--- /task ---

--- task --- Run it again. --- /task ---

See how the text (called a **string**) from the second `print` is on a new line? This is because the instruction the computer gets when you tell it to `print` is:

     1. Read the code in the brackets and figure out the result
     2. Once you’ve figured out what it says, `print` that out on the screen
     3. Put an invisible “start a new line” instruction at the end

Why does the computer need to figure out what the code in those brackets says? It's because the computer can put that string together from parts you give it.

Try it out!

--- task --- Use the following code, but put your name in between the `"` symbols where it says `"my name"`.

```python
name = "my name"
print("Hello "+name)
print("The Code, it's calling to you. Just let it in.")
```
--- /task ---

--- task --- Now run your code again and look at the result! --- /task ---

--- collapse ---
---
title: The space after "Hello"
---

You have to include a space after the "Hello", otherwise you'll just get "Hellomy name", because Python doesn't know what English looks like!

--- /collapse ---

--- collapse ---
---
title: How does the new code work?
---

You made a **variable** called `name`. A variable is like a box inside the computer with a label on it. You can put anything you want in it. Then, you can use the label to get Python to go fetch the thing that’s in the box and use it in your code.

+ So first, you created the `name` variable and stored `"my name"` in it.

+ On the next line, you used the `+` symbol followed by the variable to attach your name after the greeting at the end of the string.

--- /collapse ---

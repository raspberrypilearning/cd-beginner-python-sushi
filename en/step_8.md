## Make a number guessing game

So now you've learned about:
  * `print` statements for talking to your users
  * variables, which are a way to get our program to remember and update values
  * strings, which are pieces of text
  * `input` for getting information from our user
  * maths: how to do maths with a number
  * integers, which are numbers for doing maths with  
  * `if` statements, to make your code do something based on a condition
  * `while` loops, to make your code keep doing something until a condition isn't true

You can use these tools and commands to make this game:
  * There is a number (an integer), between 1 and 9, that the program picks in secret
  * Players have 5 guesses to pick the number
  * The game teaches players the rules
  * Players are told after each guess whether the number is lower, higher, or correct, and how many guesses they have left
  * If players gets their guess right, they get a special winning message
  * If players gets their fifth guess wrong, the game is over and they lose  

You can play an example of the game at [dojo.soy/py-dice](http://dojo.soy/py-dice){:target="blank"}.

You're missing just one thing to be able to write this game: a way to get a random number between 1 and 9. The code to do this is a little beyond what you've covered, but you can use it right now without understanding exactly how it works.

--- task ---
Put this as the **first line** in your program:
```python
from random import randint as dice
```
--- /task ---

Now, anywhere you want to use a random number between 1 and 9, just use `dice(1,9)`. For example:
```python
secret_number = dice(1,9)
```

--- task ---
Start a new Python program and try to make the game now! 
--- /task ---

Remember to use what you've learned on previous steps of this project.

Good luck!

--- hints ---

--- hint ---

You can keep track of the number of guesses players have used (or have left, depending on which way you look at it!) using a variable. You'll need to write some code to change its value after each guess.

Then write the right condition for your `while` loop to check whether players have used up all their guesses.

--- /hint ---

--- hint ---

Try using variables to store some of the other numbers too, such as the two numbers players should guess between, and the total number of guesses they are allowed.

Your program will work just fine even if you don't do this, but defining things with variables is usually a good idea. One reason is that it makes your life easier if you decide to change these values later: then the only thing you need to change is the values you assign to the variables at the top of your program, and you don't have to change all the places where you've used their values.

--- /hint ---

--- /hints ---

If you're stuck, or when you're done, you can check my answer at [dojo.soy/python-ans](http://dojo.soy/python-ans){:target="blank"}. Don't worry if yours looks very different — that doesn't matter as long as it works.
---
layout: default
---

TODO: Add intro


Joke
----

Alert boxes are little dialog windows that pop up.  Alert boxes have an OK button that you can press to make them disappear.

Let's make a program that tells a joke.

We'll have two things in this program:

1. An alert that tells the setup for the joke (we'll show this first)
2. An alert that tells the punchline

Example code:

```js
alert("why did the chicken cross the road");
alert("to get to the other side");
```

To make an alert we type `alert` and then inside parenthesis we put some text inside a string.

Strings are the places you put text in your program.  We use double quotes around text to make strings.

Every command in our program ends with a semicolon.


Greeter
-------

TODO: Explain variables, prompts, and string concatenation

Greeter: Ask the user their name, then use another pop-up to say "Hi <name>!"

Example code:

```js
var name = prompt("What is your name?");
alert("Hi " + name + "!");
```


Madlibs Of the Amazon
---------------------

Recipe:

```js
// Put this sentence in a pop up:
// If you find yourself having to cross a piranha-infested river, here's how to do it...

// Get the user to enter an adjective

// Get the user to enter a type of liquid

// Get the user to enter a body part

// Get the user to enter a verb

// Get the user to enter a place

// Fit the user's words into this sentence, and save it in a String:
// Piranhas are more [adjective] during the day, so cross the river at
// night. Piranhas are attracted to fresh [type of liquid] and will most
// likely take a bite out of your [body part] if you [verb]. Whatever
// you do, if you have an open wound, try to find another way to get
// back to the [place]. Good luck!

// Make a pop-up for the final story. You can use \n to go to the next line.

```


World Domination
----------------

**Teacher note**: If less than 30 minutes remaining, do world domination. Otherwise, skip this one.

Here's a program that asks the user for their name and does one of two things:

1. If the name is `Trey`, an alert will say that we have the same name.
2. If the name is not `Trey`, an alert will greet the user.

```js
var name = prompt("What is your name?");
if (name === "Trey") {
    alert("Hey that's my name too!");
} else {
    alert("Hi " + name + "!");
}
```

The curly braces here denote a block of code.  We put curly braces after the `if` and `else` statements so JavaScript knows what it should do in each case.  JavaScript doesn't care about indentation; we just indent to make our code more readable.

The thing inside the parenthesis next to our `if` statement is called a condition. We can use three equals signs to compare our `name` variable to the string `"Trey"` in the condition.  If this statement is true, the first code block (inside the curly braces) will be run, otherwise the code block after the `else` statement will be run.

Recipe:

```js
// 1. Ask the user if they know how to write code.

// 2. If they say "yes", tell them they will rule the world.

// 3. Otherwise, wish them good luck finding a job.
```


Magic 8 Ball
------------

How can we generate random numbers?

We can generate a random number by using `Math.random()`.  This will give us a decimal number between 0 and 1.

But we want a whole number between two other numbers.

We can multiply our number by 4 to get a random number between 0 and 4 and then we can use the `Math.floor` function to round it so we'll get either `0`, `1`, or `3`:

```js
var random = Math.floor(Math.random() * 4);
```

Recipe:

```js
// 1. Make a variable that will hold a random number and put a random number into this variable using "Math.floor(Math.random() * 4);"

// 2. Print out this variable

// 3. Get the user to enter a question for the 8 ball

// 4. If the random number is 0

// -- tell the user "Yes"

// 5. If the random number is 1

// -- tell the user "No"

// 6. If the random number is 2

// -- tell the user "Maybe you should ask Google?"

// 7. If the random number is 3

// -- write your own answer
```

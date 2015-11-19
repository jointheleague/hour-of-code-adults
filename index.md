---
layout: default
---

TODO: Add intro

Joke
----

TODO: Show how to use pop-ups (alerts)

Joke: Make a pop-up that tells a joke and a separate one for the punchline.

Example code:

```js
alert("why did the chicken cross the road");
alert("to get to the other side");
```


Greeter
-------

TODO: Explain variables and prompts

Greeter: Ask the user their name, then use another pop-up to say "Hi <name>!"

Example code:

```js
var name = prompt("What is your name?");
alert("Hi " + name + "!");
```


Madlibs Of the Amazon
---------------------

If less than 30 minutes into workshop, do madlibs. Otherwise, skip and do world domination next.

Recipe:

```js
var MadlibsOfTheAmazon = {
  main: function() {
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

  }
}
MadlibsOfTheAmazon.main();
```


World Domination
----------------

TODO: Explain if/else

TODO: Show how to generate a random number

Recipe:

```js
var WorldDomination = {
  main: function(){
    // 1. Ask the user if they know how to write code.

    // 2. If they say "yes", tell them they will rule the world.

    // 3. Otherwise, wish them good luck finding a job.
  }
}

WorldDomination.main();
```


Magic 8 Ball
------------

Recipe:

```js
var Magic8Ball = {
// 1. Make a main method that includes all the steps below….

    // 2. Make a variable that will hold a random number and put a random number into this variable using "Math.floor(Math.random() * (4 - 0));"

    // 3. Print out this variable

    // 4. Get the user to enter a question for the 8 ball

    // 5. If the random number is 0

    // -- tell the user "Yes"

    // 6. If the random number is 1

    // -- tell the user "No"

    // 7. If the random number is 2

    // -- tell the user "Maybe you should ask Google?"

    // 8. If the random number is 3

    // -- write your own answer
  }

}
Magic8Ball.main();
```


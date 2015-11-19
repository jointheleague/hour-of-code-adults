Madlibs of the Amazon
---------------------

```js
var MadlibsOfTheAmazon = {
  main: function() {
    // Put this sentence in a pop up:
    alert("If you find yourself having to cross a piranha-infested river, here's how to do it...");

    // Get the user to enter an adjective
    var adjective = prompt("Please enter an adjective", "Red");
    // Get the user to enter a type of liquid
    var liquid = prompt("Please enter a type of liquid", "Water");
    // Get the user to enter a body part
    var bodyPart = prompt("Please enter a body part", "Eye");
    // Get the user to enter a verb
    var verb = prompt("Please enter a verb", "Ran");
    // Get the user to enter a place
    var place = prompt("Please enter a place", "Paris");

    // Fit the user's words into this sentence, and save it in a String:
    var output = "Piranhas are more " + adjective +
      " during the day, so cross the river at night. Piranhas are attracted to fresh " +
      liquid + " and will most likely take a bite out of your " +
      bodyPart + " if you " + verb +
      ". Whatever you do, if you have an open wound, try to find another way to get back to the " +
      place + ". Good luck!";

    // Make a pop-up for the final story. You can use \n to go to the next line.
    alert(output);
  }
}

MadlibsOfTheAmazon.main();
```


World Domination
----------------

```js
var WorldDomination = {
  main: function(){
    // 1. Ask the user if they know how to write code.
    var answer = prompt("Do you know how to write code?");

    // 2. If they say "yes", tell them they will rule the world.
    if(answer == "yes"){
      alert("You will rule the world!!");
    } else {
    // 3. Otherwise, wish them good luck finding a job.
      alert("Good luck finding a job");
    }
  }
}

WorldDomination.main();
```


Magic 8 Ball
------------

```js
var Magic8Ball = {
  // 1. Make a main method that includes all the steps below….
  main: function() {

    // 2. Make a variable that will hold a random number and put a random number into this variable using "Math.floor(Math.random() * (4 - 0));"
    var random = Math.floor(Math.random() * (4 - 0));

    // 3. Print out this variable
    alert(random);

    // 4. Get the user to enter a question for the 8 ball
    var question = prompt("Please enter your question");

    // 5. If the random number is 0
    if (random === 0) {
      alert("Yes");
    } else if (random === 1) {
      alert("No");
    } else if (random === 2) {
      alert("Maybe you should ask Google?");
    } else {
      alert("Your mom says " + question);
    }
  }

}
Magic8Ball.main();
```

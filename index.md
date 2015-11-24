---
layout: default
---

Intro
----
Have you played with code.org already?	//show of hands

This is the code behind the blocks. The kind of code that professional programmers use.

How to use SketchPad
----
1. Students open sketchpad.cc
2. Click “Create New Sketch”
3. Press the play button.
4. Change some numbers the code and see what happens. //allow them to experiment for 3  mins
5. Delete all this code to start fresh...

Ellipse
----
Whiteboard: 

```js
ellipse(50, 50, 50, 50);
```
Challenge #1: Adjust the numbers to figure out what they mean.	//interact with students to derive (x, y, width, height)

Challenge #2: Make a face by adding eyes.

Color
----
Whiteboard:

```js
fill(255, 0, 0);    
//gives RED
//the 3 numbers stand for red, green and blue
//range from 0 to 255
```
Challenge: Add your favorite color. There are lots at rgbchart.com

Interaction
----
**Delete all the code.**

To make a sketch interactive we need to use 2 special methods. 

The things we want to happen only once go into the setup() method.

The things we want to animate go into the draw() method.

Whiteboard:

```js
void setup()
{
    
    
}
void draw()
{
    
     
}
```


Size
----
Whiteboard:

```js
size(width, height);
```
Challenge: Increase the canvas size.

**Teacher note**: If you put the size command after the ellipse command, it will wipe out the ellipse.

Greeter
-------

Let's make a greeter program. This program will ask the user their name, then say hi to them.

Example code:

```js
var name = prompt("What is your name?");
alert("Hi " + name + "!");
```

This `prompt` function makes a pop up box that says something and allows the user to enter some text.

The `prompt` function returns the text the user entered.  We can capture this text by putting it in a variable.

We can define a variable with `var` and the name of the variable.  We can put the `prompt` function call on the other side of an equal sign to capture value into this variable.

To use this variable we type its name.  We can put the text inside our variable next to other text by using a `+` sign.  The `+` sign performs string concatenation, which is just a fancy way of saying it puts strings next to each other.


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

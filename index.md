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


A basic sketch
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
Challenge: Have students copy from whiteboard.


Size & Background
----
Whiteboard:

```js
size(width, height);
background(red, green, blue);
```
Challenge: Make a large canvas with a nice background color. **Put it in the setup method.**

**Teacher note**: If you put the size command after the ellipse command, it will wipe out the ellipse.


Add a shape
-------
Whiteboard:

```js
ellipse(x, y, width, height);
rect(x, y, width, height);
//there are more at processing.org/reference
```

Challenge: Choose a shape. **Put it in the draw method.**


Interaction
----
These special variables show the co-ordinates of the mouse. //illustrate on the whiteboard

```js
mouseX
mouseY
```
Challenge: Use these variables instead of numbers in your shape.

if/else
---------------------
Whiteboard:

```js
if(mousePressed)
    fill(0, 255, 0);
else 
    fill(0, 0, 255);
```
Challenge: Make the color of your shape change when the mouse is pressed.


**Allow students to experiment and get creative with what they have learned.**



[Optional]
----
Whiteboard:

```js
random(255);    //in place of fill numbers
text("your name", x, y);    //to sign your sketch
```

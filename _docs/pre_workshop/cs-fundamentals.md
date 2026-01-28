---
title: CS Fundamentals
post-image:
description:
tags:
- cs
---
There is quite a bit of Computer science terminology that needs to be understood in order to 
effectively teach these courses. Below, we will have a definition of a term, and an example in 
real time through our intro-alice-starter world in order to effectively grasp the meaning. Each 
section is broken up by the terminology that is neccessary for teaching the following lesson 
plan. First we have Beaded Bag, then Horses, finishing with some general terms that may be 
useful. It is organized this way because the Horses plan is more complex, and requires 
tunderstanding of the terminology out of Beaded bag too.
## Beaded Bag Computer Science Content
This section should provide computer science content neccessary to understand in order to 
teach the Beaded bag lesson. 

### Algorithm

An algorithm is a sequence of steps to solve a problem or perform a task. 
Similar to changing a tire or following a recipe to bake a cake, these actions 
take a specific step-by-step processes. In Alice, the algorithms we develop help 
to animate the virtual world.

### Algorithm example

Pull up the intro-alice-starter world in Alice with an empty space in the world.my first method.
 If you have leftover methods from the previous section, you can either delete them by right 
clicking on each of them or you can open up a fresh started world be re-downloading the file. 
![](https://montanastorytelling.github.io/alice-lessons-pd/assets/img/alice_intro_world2.png)
Grab the "Do in order" block from below and place it into your world.my first method. This is 
depicted in the image above and highlighted by the red box. Once you place this into your 
world.my first method, we need to populate it with actions. You can decide to use any actions 
from the two characters in order to craft your algorithm. My algorithm moves the athlete up, 
spins the horse, and then turns the horse to face the athlete. You can also make the characters 
say certain things, or move in other ways. Once you've made your algorithm, play it with the top left button named "Play".
 Below is an image of my algorithm in the world.my first method. 
![](https://montanastorytelling.github.io/alice-lessons-pd/assets/img/alice_intro_world3.png)

### Code

Computer code is how computer users enter instructions for the computer to 
understand the stepby-step instructions. Computer scientists use a programming 
language to write code. Java, Python, and
C++ are all examples of programming languages. In Alice, this process is 
resembled through drag and drop
code blocks allowing users to create programs through visually organizing and 
connecting these code blocks. 

### Code example

In our Alice environment the code is represented in the world.my first method section. This 
details all our code, and that code tells Alice how to properly represent our commands to the 
final animation.

### Sequential 

The order in which instructions (lines of code) are executed makes a difference. 
If you were
to run straight for one mile, turn left, then run straight for two miles, you 
will be in a different spot than
if you run straight for two miles, turn left, then run straight for one mile. 
Often, in a comptuer, code is
executed sequentially, or, in the order in which it appears line-by-line. For 
example, in Alice, calling the
jump command followed by the run command will make a character first jump up 
and then, second, run.

### Sequential example

In your Alice world, you made an algorithm that is sequential. What happens if you switch 
around the ordering to some of your actions? A different animation will play. This is important
 to note when talking about animating a story. The sequence of events matter in order to 
guarantee that you animate what you want.

### Parallel

A parallel event is when two actions happen at the same time. In Alice, this 
parallel function is
called a do-together block. For example, imagine two characters walking 
side-by-side, the user would use a
do-together block to make both characters start walking at the same time.

### Parallel example

Similarly to how we can sequentially play out events, we can also play out events together. If 
you take the block "Do together" from below and move it into your world.my first method, 
you can move all of your algorithm into the "Do together" block and see how things change. If
 you want to delete the "Do in order" block afterwards, right click on it and then select 
"delete". Play your animation to see the difference!

## Horses Computer Science Content
This section should provide computer science content neccessary to understand in order to 
teach the Horses lesson. 

### Boolean 

A boolean (true/false) is a type of variable that can take one of two values: 
true or false.
Booleans can be used as the condition in a conditional (if/then) statement or as 
a condition (sometimes
called the loop guard) in a while loop. In Alice, functions can return a boolean 
variable. For example, the
world has a function “both a and b” that takes as input two booleans, a and b, 
and returns true if both are
true, and false if otherwise.

### Comment

A comment is a region of text in code that is not meant to be executed, but 
instead provides
information about the executable code around it.

### Conditional Statement

A conditional (if/then) statement controls whether or not certain lines of code
are executed. A boolean (true/false) value or expression is given as input, and 
if that value is true, then the
code is executed. For this reason, conditional statements are sometimes referred 
to as if/then statements.
In Alice, if/else blocks can be found at the bottom of the programming 
environment, all if blocks have an
else block that follows. Code in the else block is executed if the input value 
is false. We see conditional
statements in everyday language as well! For example: **if** the day is 
Monday, **then** we go to school.

### Property

A property is a variable that describes an object. In Alice, all objects (e.g., 
horse) have
properties, including skin texture and isShowing. You can see the list of 
properties for an object by
clicking on the object in your scene, then select in the properties tab under 
objects details in the
bottom left hand corner.

### Variable

A variable is a value that stores information to describe an object or method. 
The value can be
a number (e.g., height), a string (e.g., name), or even a color. In Alice, for 
example, a variable is used when
the user wants to specify the number of jumps an object should take.

## General Computer Science Content

This section should provide some general computer science content that may help 
with any/all the lesson plans.
### Event

How does a computer know when to run an algorithm?
In Alice, we will use the command: "When the world starts..."
(do the following stuff). Computers "listen" for events to occur,
and when they "hear" an event, they run some code.

#### Examples of Events

* When a key is pressed...
* When a mouse is clicked...
* When a screen is touched...

### Sequencing

In Alice, code runs sequentially one block after another. Sequencing refers to the order in which things happen in your code.

#### Linear Sequencing

Linear Sequencing is when two things happen in code one after another, for 
example:
"When world starts...  jump then spin." The object will jump up, come back down to its original position, and then spin. Spin does not run until after the jump sequence ends.

#### Parallel Sequencing:

Parallel Sequencing is when two things happen in code at the same time, for 
example:
"When world starts... do together{jump then spin}. The object will initiate the 
jump and spin sequences at the same time. The object will jump up and spin and 
then come back down.

---
layout: page
title: Friday Self-guided Tutorial
permalink: /fridaytutorial/
---

This is the self-guided, self-paced tutorial for Friday evening.  We've included a break in the middle, but remember to take a break to stretch, get some water, take a moment to relax any time you need to.

As you go through this tutorial, any time you see something like this:

`a = "Hello"`

it's something that you can type in at the `>>>` prompt in your Python shell.  Hit Return or Enter after every line and note the output (although sometimes there won't be any!).  Don't copy and paste -- you'll learn much better if you take the time to type everything yourself.

###Math

Math in Python looks a lot like math with a calculator.

####Addition

`2 + 2`

`1.65 + 2.15`

####Subtraction

`12 - 5`

`45.9 - 25.3`

`45.9 - 61.7`

####Multiplication
Multiplication uses the `*` (asterisk or star) symbol.

`6 * 7`

`5.6 * 4.3`

####Division
Division uses the `/` symbol.

`12/3`

`16/5`

> Note: If you've used Python 2, you'll see that division works differently in Python 3.  Python 2 uses floor division for integers, meaning it will return only the whole number part of the answer. Python 3 performs true division, returning the real or true value of the division.

###Types

There's a helpful function (more on what a function is later) called `type` that tells you what kind of thing -- what data type -- Python thinks something is. We can check for ourselves that Python considers '1' and '1.0' to be different data types:

`type(1)`
`type(1.0)`

So now we've seen two data types: *integers* and *floats*.  We'll see more data types as we work through the lesson.

We used the term 'function' without explaining what it is -- we'll talk about functions more in a bit, and write our own, but for now know these things:

* Functions encapsulate some useful bit of work. We save that useful bit of work inside the function so we don't have to type it over and over again every time we want to use it. So, for example, some nice person decided that being able to determine the type of an object was useful, so he or she put the Python code that figures out an object's type into the function `type()`, and now we all get to use it, instead of having to write it ourselves.
* Functions are sort of like functions in math class. You provide input to a function and it produces output. The `type()` function takes data as an input, and produces what type of data the data is (e.g. an integer or a float) as output.
* To use a function, write the name of the function followed by an open parenthesis, what the function takes as input (we call that input the arguments to the function), and then a close parenthesis.

So in this case 'type' is the name of the function, and it takes one argument; in the example we first give type an argument of 1 and then give it an argument of 1.0.


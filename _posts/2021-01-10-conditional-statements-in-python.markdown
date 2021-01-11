---
layout: post
title: Conditional statements in python
date:   2021-01-10 23:50:33 +0530
description: 
img: post-18.png
tags: [Blog, python, programming]
author: Aswin Barath
---
In programming, conditions are what gives a language the power to showcase intelligence, by controlling the flow of a program.

That's why conditional statements are also referred as Control flow tools in a programming language.

And python uses the usual flow control statements known from other programming languages, with some twists.

Let's start with the basic one:
## `if` statement
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/0e4gq0vhbwiuu0ud7a0b.png)
Output:
```
Please enter your age: 19
You are allowed to view R-rated series on Netflix
```

The above code is a good way to check one's age and display an action to be performed, but wouldn't be nice to have an alternate message to pop up if one's age is under 18.

That's where we may use elif or else statements, and let's look how an if else combination would look like:
## `if else` statements
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/264gnh0j9i0ql8nxiz6e.png)
Output:
```
Please enter your age: 17
Under 17 requires accompanying parent or adult guardian to view R-rated series on Netflix
```

As you can see this code provides better context than previous one and delivers an 'either or' output based on the given user input.

What if we level up this code by giving in multiple inputs and writing some sophisticated conditions so that we get to check with the rating and corresponding age limit.

This is where we get to use the if ... elif ... elif ... else sequence of conditional statements:
## `if … elif … else` statements
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/zst258l8q1jnvfiicmyo.png)
Output:
```
Please enter the film rating: NC-17
Please enter your age: 17
You are not allowed to view the film
```
As you can see this code, it checks the age and rating corresponding to the input to provide you accurate details on parental guidance. Cool, right?

And, by the way, if you're wondering about the code having multiple if ... elif ... if ... elif statements, don't worry.

I've used something called as nested condtional statements where one can write if .. elif .. else statement inside any of the `if` `elif` `else` statements by nesting under each other.

### A Quick Note:
* There can be zero or more `elif` parts, and the `else` part is optional.
* The keyword ‘elif’ is short for ‘else if’, and is useful to avoid excessive indentation.
* An if … elif … elif … sequence is a substitute for the `switch` or `case` statements found in other programming languages.

#### Code along and have fun ;)

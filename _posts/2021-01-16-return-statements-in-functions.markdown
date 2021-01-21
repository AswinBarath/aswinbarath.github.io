---
layout: post
title: the return statements in functions
date:   2021-01-16 23:19:04 +0530
description: Explore more on functions throughreturn statements.
img: post-24.png
tags: [Blog, python, programming, codenewbie]
author: Aswin Barath
---
*Let me start with a fact: Every function returns a value when called.*

Well, I don't know about you, but I was surprised to know about it in the first place!

Let's see an example to prove my point:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/gzo8m0us2lrw708ob1la.png)

Output:
```
Welcome to my blog post
None
```

Did you see that?
When I called the function, it has returned the special type `None`.
The variable `post` stores it and prints it out in the second line.


Now, we can explicitly return a value from a function by using the `return` keyword.

## return statement
* The return statement includes a `return` keyword followed by an expression.
* An expression is a set of conditions which produces a value.
* So, the return statement can contain an expression or an explicit value to be returned.
* A return statement also ends the function execution. This means that any statements inside a function following the return statement will not be executed.
* Take a **note** that return statement cannot be used outside a function.

Let's code a few examples:

### 1) Single return statement
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/p29se4137v6npd84jsfb.png)
Output:
```
21
```
As you can see in this example, we have given an expression which returns the product of given two numbers.

### 2) Multiple return statements
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/0ebk7v1ygydcisjgbnpi.png)
Output:
```
21
3.14
Try again!
```
Here, an explicit value is specified in multiple return statements.

### 3) return statement with multiple values
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/zuec2h0t0f967vai6p4y.png)
Output:
```
(21, 63, 210)
```
This example returns dynamic values in a tuple based on the given argument.

#### Code along and have fun.
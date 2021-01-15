---
layout: post
title: functions in python
date:   2021-01-14 23:58:26 +0530
description: A function is a piece of code.
img: post-23.jpg
tags: [Blog, python, programming, codenewbie]
author: Aswin Barath
---
## Alright, let's start with what functions actually are?
* OK, a **function** is a piece of code.
* A function may/may not accept input(s).
* A function may/may not return an output(s).

## Why do we need functions in a program?

* Well, the **Reusability** of the code in a program is made possible through functions.
* The program can call these so-called *functions*, *n* - number of times.
* This showcases the best practice in a program called **DRY**.

## DRY - Do not Repeat Yourself 
* A code is said to be DRY if any given code does not repeat certain tasks
* A *function* implements this just by writing once and using whenever necessary.

## Quick intro to functions in python

### Creating a function
* To create a function we use the keyword `def`.
* `def` must be followed by the function name.
* followed by a parenthesis filled with formal parameters(parameters).
* The statements that follow up makes the body of the function.
* **Note:** Any code written inside a function must be indented.
* Let's see an example where I thank every one of my readers:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/lcfr9b09yvqq8ej8wzso.png)

### Calling a function
* To call a function we use the function name followed by parenthesis filled with actual parameter(arguments).
* This is when the code inside the function actually gets executed.
* Let's see the same example and its output:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/ldpjd972olmmhxst9gny.png)
* Output:
```
Hello there John Doe
Thank you for taking your time to read my post ;)
Hello there Jane Doe
Thank you for taking your time to read my post ;)
```

### Passing values to a function
* Didn't you notice passing values to a function already?
* We can pass values to a function through the function call.
* We do this by writing the values inside the parenthesis of a function call.
* Consider the above example:
```
reader("John Doe")
reader("Jane Doe")
```
* The function call `reader()` passes the values "John Doe" and "Jane Doe" as arguments to the function.


*There you go, now you can create your own functions and play with it.*

### Code along and fun.

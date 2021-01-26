---
layout: post
title: Arguments and parameters in function
date:   2021-01-17 22:08:45 +0530
description: In general, the term parameters and arguments are being used interchangeably.
img: post-25.png
tags: [Blog, python, programming, codenewbie]
author: Aswin Barath
---
In general, the term parameters and arguments are being used interchangeably.

Although, with respect to a function:
* **parameters** are the variables listed inside the parentheses in the function definition.
* **arguments** are the values that are sent to the function when it is called.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/3uegbayvsoqmsci8lemd.png)

It turns out that it's possible to define functions with various types of arguments in **python**.
And there are three types of arguments/parameters, which can be combined.

## 1) Default Argument Values
* The most useful type of argument is to specify a default value for one or more arguments, inside the parenthesis of a function definition.
* This creates a function which is flexible to use.
* Because this function can be called with fewer arguments than it is defined to allow.
* Let's look at an example:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/t5jazknupedndedxv22i.png)
Output:
```
You have 120 minutes!
Let's watch a action type web series
You have 150 minutes!
Let's watch a thriller type web series
You have 200 minutes!
Let's watch a horror type movie
```
This function is called in several ways:
* giving only the mandatory argument: `popcorn_time(120) `
* giving one of the optional arguments: `popcorn_time(150, 'thriller') `
* or even giving all arguments: `popcorn_time(200, 'horror', 'movie') `

[Play with the code here](https://repl.it/talk/share/Default-Arguments/117463)


## 2) Keyword Arguments
* Functions can also be called using keyword arguments of the form kwarg=value.
* For instance, consider the above example of `popcorn_time`, function which accepts one required argument(`time`) and two optional arguments(`genre`, `watch`)
* This function can be called in any of the following ways:

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/fg9eep71i5yxaqeyjoxy.png)

* But take a note that, the following function calls would be invalid:

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/x32qb6d2s5sqed7cvmc9.png)

## 3) Special parameters
* By default, arguments may be passed to a Python function either by position or explicitly by keyword.
* For readability and performance, we can restrict the way arguments can be passed
* So, a developer needs to look at the function definition to determine if items are passed by position, by position or keyword, or by keyword.

* An advanced function definition may look like the one below:

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/hx1onjcb0zff0ffqtomf.png)

* If you're interested, check out [special parameters python docs](https://docs.python.org/3/tutorial/controlflow.html#special-parameters) for more information.



What if you don't know how many arguments you want to be passed into your function?
Python provides us with a solution:
*Arbitrary Arguments* - *args
*Arbitrary Keyword Arguments* - **kwargs

## Arbitrary Arguments, *args
* To specify the argument as an arbitrary argument, you need to just add a *(asterisk) before the parameter name in the function definition.
* The function, in turn, will receive the arguments and save it as a tuple of arguments, and you can access the items accordingly:

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/5wn0ksxwcfz3zgi6ux2i.png)

Output:
```
Largest number: 94
```

## Arbitrary Keyword Arguments, **kwargs
* Similarly, to specify the argument as an arbitrary keyword argument, you need to add two asterisks: ** before the parameter name in the function definition.
* The function, in turn, will receive the arguments and save it as a dictionary of arguments, and you can access the items accordingly:

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/3r5kvju2cei6dt1kgi75.png)

Output:
```
Marvel Studios presents - Iron Man
Starring - Robert Downey Jr.
Marvel Studios presents - Captain America: The First Avenger
Starring - Chris Evans
Marvel Studios presents - Thor
Starring - Chris Hemsworth
```


### Code along and have fun.

---
layout: post
title: Variables in Python
date:   2020-12-31 12:38:53 +0530
description: Variables in programming are something like containers storing some specific things. Variables are a way we store store data on computer.
img: post-8.jpeg
tags: [Blog, python, programming]
author: Aswin Barath
---
**Variables** in programming are something like containers storing some specific things.

Variables are a way we store data on the computer.
This is how we create variables in python:
~~~
Syntax:
variable_name = data
~~~
But, there's a catch here, you cannot have some crazy names as variable names in python.

There are some **best practices** in python being followed by the python community when it comes to naming your variable names.
#### Do's
* Variable names can contain *letters, numbers, underscore*
* Always start with a lowercase letter or an underscore
* **snake_case**
Use lowercase letters and underscores for spaces.
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/owvs5ml9g1sb8hhvju32.png)

#### Dont's
* Do not use reserved keywords of python as variable names, coz this is what python will tell you:
~~~
...
Traceback (most recent call last):
  File "./program.py", line (x), in <module>
...
~~~

* Do not use special characters like !,@,#,$,%,^,&,* in a variable name, coz you will get the same error message:
~~~
...
Traceback (most recent call last):
  File "./program.py", line (x), in <module>
...
~~~

#### Note
Keep in mind that python is case - sensitive, which means the variable like hello and Hello are very different for python.

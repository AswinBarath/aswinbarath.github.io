---
layout: post
title: Basic jump statements in python
date:   2021-01-12 23:42:39 +0530
description: Jump statements can be used to modify the behaviour of conditional and iterative statements.
img: post-20.jpeg
tags: [Blog, python, programming]
author: Aswin Barath
---
Jump statements can be used to modify the behaviour of conditional and iterative statements.

`break` and `continue` statements fall under the *jump statements* category.

## `break` statement
* The `break` statement, borrowed from C programming language, breaks out of the current loop when encountered.
* So, any further iterations will not be executed as the `break` statement changed the flow of the program by coming out of the loop.

Example:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/brwou461bmtjy0h0fkti.png)

Output:
```
Searching...
Searching...
Searching...
Searching...
Found the treasure
```

## `continue` statement
* The `continue` statement, borrowed from C programming language, continues with the next iteration of the loop when encountered.
* So, any code following the `continue` statement in a loop will be skipped and the loop will continue the next iteration.

Example:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/tf9b98bbey2h0oj3wgyl.png)

Output:
```
Found an even number 2
Found an odd number 3
Found an even number 4
Found an odd number 5
Found an even number 6
Found an odd number 7
Found an even number 8
Found an odd number 9
```


#### Code along and have fun.

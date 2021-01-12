---
layout: post
title: Getting input in python
date:   2021-01-02 12:52:44 +0530
description: Getting input from the user is what makes a program more interactive with the user.
img: post-9.png
tags: [Blog, python, programming]
author: Aswin Barath
---
Getting input from the user is what makes a program more interactive with the user.

Hence, in python we have an input function: **input()**, to receive input from the user.

Take a look at an example.
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/e3sp4ikfalv5h6fkmt0d.png)
Output:
```
Enter any data:Happy new year!
Happy new year!
```

## input function under the hood
* When *input()* function is encountered by python, the program will pause until the user enters data.
* Later, any input entered by the user will be converted into a *string*. Let's see another example to understand this point.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/cp4cys4cxrykhdi831tu.png)
Output:
```
Enter any text: Have a great year ahead.
text: Have a great year ahead. , type: <class 'str'>
Enter any number: 2021
number: 2021 , type: <class 'str'>
```

* So, in these cases make sure that you convert the input to your preferred data type using its corresponding constructors. Let's see that example too.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/7igk9a1p5mmnrtga77ln.png)
Output:
```
Enter any number: 2021
number: 2021 , type: <class 'int'>
```

**So, code along and have fun :)**

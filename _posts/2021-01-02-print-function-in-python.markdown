---
layout: post
title: print function in python
date:   2021-01-02 14:13:39 +0530
description: print() function and input() function makes the program more interactive with the user.
img: post-10.png
tags: [Blog, python, programming]
author: Aswin Barath
---
**print()** function and [*input() function*](https://lnkd.in/eXDgD-r) makes the program more interactive with the user.

Although, there are some extra things we can do with *print()* which makes the output formattable.

## Functionalities of print() function
* Let's start with the syntax:
`print(object(s), sep=separator, end=end, file=file, flush=flush)`
* *Fact: In python, all data types are implemented as an object.*
* *object(s)*: Will accepts any number of objects, which will be converted into a string before printed. We can pass it in two way:
1. Concatenated:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/d862yfw68qch0xg4yza2.png)
2. Comma seperated:
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/avb86wz6301z7h6d0f42.png)
Output:
```
Enter any number: 2021
year:2021
```

* *sep='separator'*: This is Optional.
Used to specify how to separate the objects, if there is more than one.
Default is ' ' (space).
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/zzzxl27vj0sognuihgjj.png)
Output:
```
Enter any number: 2021
year:   2021
```
* *end='end'*:  This is Optional.
Used to specify what to print at the end.
Default is '\n' (new line).
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/ytgicradt44tei2tgogp.png)
Output:
```
Enter any number: 2021
year: 2021  month: Jan
```
* *file*: This is Optional. Default is sys.stdout. Used to specify the name of the file to write the output. If the file doesn't exist, it will create a new file.
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/hzmz2vapi8vgwlr4zshy.png)
Output (in 'Greetings.txt' file):
```
!!!	Wish you a happy new year	!!!
Enjoy the year--->2021---> and the month --->January

```

* *flush*: This is Optional. A Boolean, specifying if the output is flushed (True) or buffered (False). Default is False.

* [Check out this GFG article for a detailed explanation of the flush parameter](https://www.geeksforgeeks.org/python-sys-stdout-flush/)

### And, that's it for today. Code along and have fun ;)

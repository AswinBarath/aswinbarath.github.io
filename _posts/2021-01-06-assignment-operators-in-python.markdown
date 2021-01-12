---
layout: post
title: Assignment Operators in python
date:   2021-01-06 15:13:46 +0530
description: Assignment operators are used to assigning values to variables.
img: post-14.png
tags: [Blog, python, programming]
author: Aswin Barath
---
Assignment operators are used to assigning values to variables.

That is to store values in variables we use `=` assignment operator.
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/suvm5dg0a7deu6t5z7wx.png)
Output:
```
3.14
```
OK, now comes the real fun.
Have ever been tired to use `x = x + 5`, where we type the variable x twice?
There's actually a shortcut for this called **Augmented assignment operators**.

*Augmented assignment operators* can be used as a replacement as follows:

```
x += 3	   --->	   x = x + 3	
x -= 3	   --->	   x = x - 3	
x *= 3	   --->	   x = x * 3	
x /= 3	   --->	   x = x / 3	
x %= 3	   --->	   x = x % 3	
x //= 3	   --->	   x = x // 3	
x **= 3	   --->	   x = x ** 3	
x &= 3	   --->	   x = x & 3	
x |= 3	   --->	   x = x | 3	
x ^= 3	   --->	   x = x ^ 3	
x >>= 3	   --->	   x = x >> 3	
x <<= 3	   --->	   x = x << 3
```
## Here's the Code and Output

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/m06p70zukbkszx1v3idd.png)
```
9
6
18
6.0
```


![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/0rrm332uuwdnfs6wdhwe.png)
```
64
1
0
```


![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/yhvrfs2geb1wn5n9yl4z.png)
```
2
3
```


![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/j93ngv49xkrczeq1yl47.png)
```
0
3
24
```

**Quick Note**: The code snippets reuses the same variable to assign with different [arithmetic operations](https://dev.to/aswin2001barath/arithmetic-operators-in-python-3lgc) / [bitwise operations](https://dev.to/aswin2001barath/bitwise-operators-in-python-4pii) / [shift operations](https://dev.to/aswin2001barath/bitwise-operators-in-python-4pii).

So, while coding makes sure you practice to use print statements after each operation.

#### Code along and have fun ;)

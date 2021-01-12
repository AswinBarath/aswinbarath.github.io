---
layout: post
title: Comparison Operators in python
date:   2021-01-05 20:28:04 +0530
description: So, basically, comparison operators are used to comparing two values that are numbers.
img: post-13.png
tags: [Blog, python, programming]
author: Aswin Barath
---
So, basically, comparison operators are used to comparing two values that are numbers.

If we level up to be geeky, comparison operators can also be used to compare other data types.

Now, let's start with equality checks and I hope you like spider-man movies.

## `==` Equal comparison operator
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/guzfmp3q00om6stqm5n2.png)
Output:
```
False
True
```

## `!=` Not Equal comparison operator
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/h38d9uugwlg7xkhuin00.png)
Output:
```
True
False
```

Alright, I'm sure that you are aware of how to use other operators to compare two number values, right?
OK, now's the time to level up to be geeky.

For the rest of the operators let us compare the letters from the Alphabet.
Wait, what?!
You heard me right!

Let me explain it at the end of this post.


## `>` Greater than comparison operator
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/0u7bnt0362wi8jbzljbb.png)
Output:
```
False
True
False
```

## `<` Less than comparison operator
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/eqeovwuhquvs5haea3t9.png)
Output:
```
True
True
False
```

## `>=` Greater than or equal to comparison operator
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/dgq5vzzy34xfsrkp1ese.png)
Output:
```
False
True
True
```

## `<=` Less than or equal to comparison operator
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/tdfv1egzgn8jh9peawv7.png)
Output:
```
False
True
True
```

Here's the answer for the above craziness.

When we compare two letters (or characters), it gets converted into [ASCII code](https://www.ascii-code.com/). You can check the link where the table contains 'DEC' (Decimal values) for the characters from Alphabet.

Now that the characters are converted into ASCII code, which is nothing but numbers and we are back to square one.
That is, we can compare the values as numbers and return True or false.

### Code along and have fun ;)

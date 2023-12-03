# Data Types and Operators

## Overview:
* What are "Data types"?
* Basic Data Types
* Storing data in Variables
* Operators
* Types of operators
* Doing math with arithmetic operators
* String concatenation and replication

## What are "Data Types"?
In Python (and computer programming in general), you can think of a data type as a label for a certain kind of value.
For example:

`42 is a number, Data is a word, B is a letter`

Number, word and letter are used to classify each value in this sentence, this isn't programming, it's just plain English.
If i asked you to think of a number, you probably wouldn't be thinking of 'B' or 'Z', this is because we have learnt to tell different kinds of values apart. Now we will be learning the same thing, not in the English language but in the Python programming language.

## Basic Data Types
The Python programming language comes with a few built-in data types, but for this article we will focus on four of them, which are:

* `int` (Integer)
* `float` (Floating Point)
* `str` (String)
* `bool` (Boolean)

They probably don't seem as obvious as number, word and letter that we discussed earlier, but you'll get used to it quickly, I promise ;)

### `int` (Integer)
If you are already familiar with the concept of Integers in Basic Mathematics, then you're good, it basically means the same thing here. All positive and negative whole numbers belong to this category of values called Integers.

In Python, Integers are represented by the `int` data type.

Look at these examples:
```
42 is an int
593 is an int
-69 is an int
B is not an int
"data" is not an int
9.8 is not an int
4.0 is not an int
-0.1 is not an int
```

You might be thinking, "Hey, isn't 4.0 a positive whole number?", yes, you are correct.

$4.0 = 4$

but Python doesn't accept any number with a decimal point as an `int`.

So this means, an integer in Python is any positive or negative whole number without any decimal points.

### `float` (Floating Point)
The concept of floating point numbers might not seem familiar to you if this is your first time learning a programming language, but you can just think of them as numbers with a decimal point.

In Python, floating point numbers are represented by the `float` data type.

Look at these examples:
```
42 is not a float
42.0 is a float
3.14 is a float
"float" is not a float
-9.8 is a float
```

That wasn't too hard was it? Let's continue.

### `str` (String)
Strings are used to represent text, you can think of a string as a sequence of single characters.

For example:

"data" is a string, it is a sequence of letters `d, a, t, a`.

"42" is a string, it is a sequence of numbers `4, 2`

Now you're probably thinking
> **Wait, WHAT!!**
>
> "42" is a string? shouldn't that be an integer?

There is a difference between `42` and `"42"` in Python, anything that is enclosed by single or double quotes is considered a string. So, if you put an integer or a float in quotes, it now becomes a string.

In Python, strings are represented by the `str` data type.

Look at these examples:
```
"data" is a str
'word' is a str
'42' is a str
pineapple is not a str
23.0 is not a str
True is not a str
"False" is a str
```

### `bool` (Boolean)
Booleans are used to represent only two values `True` and `False`, these are logical values used to check if certain conditions are met during the execution of our program. We will be using these values a lot, directly and indirectly, when we start learning about conditionals in Python.

In Python, Booleans are represented by the `bool` data type.

Look at these examples:
```
"True" is not a bool
False is a bool
True is a bool
```
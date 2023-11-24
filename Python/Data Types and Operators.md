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

In Python Integers are represented by the `int` data type.

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
An integer can be decimal (base 10), binary (base 2), octal (base 8) and hexadecimal (base 16), but you have add some special prefixes for Python to understand.

Here's what I mean, if you tried to do a binary addition like this in Python `1 + 11`, Python would think you're trying to add two decimal integers so the result would be `12` and not `4` (`100`). By default, Python sees all integers as decimal, so you have to explicitly tell Python what number system you want an integer to be in, by using some special prefixes.

| Number system | Prefix |
|:--------:| -------------:|
| Binary | `0b` |
| Octal | `0o` |
| Hexadecimal | `0x` |

Now let's try binary addition again with the prefixes this time
```
>>> 0b1 + 0b11
4
```
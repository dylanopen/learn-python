# 1.2 - Comments

A comment is completely ignored by Python.

We can use a comment to explain how code works, or to ignore code.

## Single-line comments

We can create a single line comment using a **hashtag** (`#`):

``` python
# This is a comment
# This is also a comment
```

We can also add a comment at the end of a line:

``` python
name = "Bob"
print(name) # prints 'Bob'
```

## Commenting out code

We can also use comments to comment out code.

For example:

``` python
print("hello")
# print("not printed!")
```

Output:

``` text
hello
```

## Multi-line comments

The easiest way to create a multi-line comment is just to use lots of single-line comments:

``` python
# This program prints the
# text 'bonjour' to the
# console / terminal
print("bonjour")
```

## Strings as comments

It is not recommended, but we can use a multi-line string as a comment:

``` python
"""
This is a comment.
The code inside this string...
Never runs!
"""
print("Only this line runs!")
```

Output:

``` text
Only this line runs!
```

## Exercises

### Fixing errors

A line in the below code has an issue.

Comment out the broken line so the program can run.

``` python
printf(Hello, world!)
print("hi")
print("there's an error somewhere :(")
```

Hint: use a hashtag `#` to create a comment.

[View solution](../exercises/3.py)

### Program information

Add some comments at the top of your program explaining what the program does and who made it.

You may want to include something like this:

``` text
Program name: "Hello World"
Description: Gives the user a warm welcome
Author: <your_name>
Date: 01/10/2023
```

The program itself is a simple hello world program, like we built in the last lesson:

``` python
print("Hello world")
```

Hint: you can use hashtags or a string comment!

[View solution](../exercises/4.py)

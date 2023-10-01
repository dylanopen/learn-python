# 1.3 - Variables

## Creating a variable

We can create a variable with this syntax:

``` python
name = value
```

For example, to create the `year` variable with the value `2023`:

``` python
year = 2023
```

## Reading a variable

We can read a variable by simply typing the name.

For example:

``` python
year # 2023
```

But this isn't very useful as it is.

We need to be able to *use* this value somewhere.

## Printing a variable

To print a variable, type:

``` python
print(name)
```

... where `name` is the name of the variable.

To print the `year` variable from before:

``` python
print(year)
```

Output:

``` text
2023
```

## Using a variable

We can use a variable in many ways.

Let's explore some of the common ways.

### Copying a value

We can 'copy' the value of one variable to another:

``` python
a = 2 # create 'a'
b = a # copy 'a' into 'b'
```

Result:

``` text
a: 2
b: 2
```

### Calculations

In the code below, we use some *arithmetic operators* on variables `x` and `y`:

``` python
x = 8
y = 2

print(x + y)
print(x - y)
print(x * y)
print(x / y)
```

Output:

``` text
10
6
16
4.0
```

## Exercises

### Defining variables

Define (create) a variable called `name`.

You may set the value to whatever you would like.

Hint: use the assignment operator (`=`).

[View solution](../exercises/5.py)

### Printing variables

Using your solution for the **defining variables** exercise, print the value of `name`.

Hint: use the `print` function

[View solution](../exercises/6.py)

### Variable maths

Create 3 variables, each holding a number (int).

They should have the following values:

``` text
a: 5
b: 7
c: 4
```

Then, print the value of each variable (but add 3 to each).

You should get the following result:

``` text
a: 8
b: 10
c: 7
```

Hint: use the `print` function and the `+` operator.

[View solution](../exercises/7.py)

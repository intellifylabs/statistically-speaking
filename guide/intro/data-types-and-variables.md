# Data types and variables

In this segment, we'll be looking at Python, a high-level, interpreted programming language that is known for its simplicity and readability. Python is an excellent language for beginners and experts alike, and is often used for web development, data analysis, artificial intelligence, and more.

## Table of Contents

- [Data types and variables](#data-types-and-variables)
  - [Table of Contents](#table-of-contents)
  - [Introduction to variables](#introduction-to-variables)
  - [Basic data types](#basic-data-types)
  - [Collection data types](#collection-data-types)

---

## Introduction to variables

In Python, variables are used to store information. Variables can hold different types of data, such as numbers, text, or more complex types of data. Unlike some other languages, Python variables don't need to be declared or defined in advance.

To create a variable, you just assign it a value and then start using it. Assignment is done with a single equals sign (`=`):

```python
x = 10
```

In this example, `x` is now a variable, and it contains the value `10`.

## Basic data types

Python has several basic (primitive) data types including:

- **Integers (`int`)**: Integers represent whole numbers, positive or negative, without decimals.

```python
x = 10
y = -3
print(type(x))  # Outputs: <class 'int'>
```

- **Floating point numbers (`float`)**: Floats represent real numbers; they contain integer and fractional parts.

```python
x = 3.14
print(type(x))  # Outputs: <class 'float'>
```

- **Strings (`str`)**: Strings represent text. They are created by enclosing characters in quotes.

```python
x = "Hello, Python!"
print(type(x))  # Outputs: <class 'str'>
```

- **Booleans (`bool`)**: Booleans represent one of two values: `True` or `False`. They are often used in conditional statements.

```python
x = True
print(type(x))  # Outputs: <class 'bool'>
```

## Collection data types

In addition to the basic data types, Python has several types of collections. These are:

- **Lists (`list`)**: Lists are ordered, mutable (changeable), and allow duplicate members.

```python
my_list = [1, 2, "Python", True]
print(type(my_list))  # Outputs: <class 'list'>
```

- **Tuples (`tuple`)**: Tuples are ordered, immutable (unchangeable), and allow duplicate members.

```python
my_tuple = (1, 2, "Python", True)
print(type(my_tuple))  # Outputs: <class 'tuple'>
```

- **Sets (`set`)**: Sets are unordered, mutable, and do not allow duplicate members.

```python
my_set = {1, 2, "Python", True}
print(type(my_set))  # Outputs: <class 'set'>
```

- **Dictionaries (`dict`)**: Dictionaries are unordered, changeable, and indexed collections. They have key-value pairs.

```python
my_dict = {
    "name": "Python",
    "year": 1991
}
print(type(my_dict))  # Outputs: <class 'dict'>
```

That's a brief overview of data types and variables in Python. As you get more comfortable with Python, you'll find that these are the building blocks for more complex code.

<br />

---

<a href="/guide/intro/inferential-statistics.md">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cloud-c4m75tmer-hack-club-bot.vercel.app/0back.svg">
    <img align="left" width="70" src="https://cloud-c4m75tmer-hack-club-bot.vercel.app/0back.svg" />
  </picture>
</a>

<p align="right">
  <em>
    <b>
      <a href="/guide/visualization/importance-of-data-visualization.md">
        Importance of data visualization →
      </a>
    </b>
  </em>
</p>

<br />

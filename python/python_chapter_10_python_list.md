# 📚 Python Lists

## 🧠 What is a List?

A **list** in Python is a collection of items that are **ordered**, **changeable (mutable)**, and **allow duplicates**. Lists are written using **square brackets `[]`**.

> Example

>```python
>fruits = ["apple", "banana", "cherry"]
>```

## 📌 Important Properties of Lists

- Lists can hold elements of **different data types**

- Lists are **mutable** (can be changed)

- Lists can contain **duplicate** values

- Lists support **indexing and slicing**

___

## 🧪 Creating a List

>```python
>numbers = [1, 2, 3, 4]
>mixed = [1, "hello", 3.5, True]
>empty = []
>```

## 📏 Length of a List

You can find the **number of items** in a list using the `len()` function.

### 🔹 Syntax:
>```python
>len(list_name)
>```

>  Example

>```python
>fruits = ["apple", "banana", "cherry", "mango"]
>print(len(fruits))  # Output: 4
>```

## 🧪 List Item Data Types

A Python list can contain elements of **any data type** — even a mix of different types in the same list.

> Examples

>```python
># List with integers
>numbers = [1, 2, 3, 4]
>
># List with strings
>fruits = ["apple", "banana", "cherry"]
>
># Mixed data types
>mixed = [1, "hello", 3.5, True]
>
># List of lists (nested list)
>nested = [[1, 2], ["a", "b"]]
>```

**Output**

>```
><class 'list'>
>```
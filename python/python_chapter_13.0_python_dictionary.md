# 📘  Python Dictionaries

## 🧩 Overview
A **dictionary** in Python is an unordered, mutable collection of items where each item is a pair of a **key** and its **value**. Dictionaries are also known as **hash maps** in other programming languages.

## 🔑 Key Characteristics
- Each key must be **unique**.
- Dictionary values can be of any data type.
- Dictionaries are mutable, so you can update, add, or remove items.
- Represented with **curly braces `{}`** and key-value pairs separated by a colon `:`.

---

## 🛠️ Creating a Dictionary

```python
# Example 1: Basic dictionary
student = {
    "name": "Rahul",
    "age": 21,
    "course": "Python"
}

# Example 2: Using the dict() constructor
info = dict(city="Delhi", population=18000000)

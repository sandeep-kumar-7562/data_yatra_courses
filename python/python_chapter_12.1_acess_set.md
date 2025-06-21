# 🔍 Accessing Set Items in Python

In Python, sets are **unordered** collections, which means items do not have an index. So, you **cannot access** set items using indexing like `my_set[0]`.

However, there are several ways to **access and work with the items** in a set.

---

## ✅ Using a `for` Loop

You can loop through a set using a `for` loop to access each item.

### Example:
```python
fruits = {"apple", "banana", "cherry"}

for fruit in fruits:
    print(fruit)

# 🔍 Accessing Set Items in Python

In Python, sets are **unordered** collections, which means items do not have an index. So, you **cannot access** set items using indexing like `my_set[0]`.

However, there are several ways to **access and work with the items** in a set.

---

## ✅ Using a `for` Loop

You can loop through a set using a `for` loop to access each item.

>   Example

>```python
>fruits = {"apple", "banana", "mango"}
>
>for x in fruits:
>    print(x)
>```

**Output**

>```
>apple
>mango
>banana
>```

**Check if "mango" is present in the set**

>  example

>```python
>fruits = {"apple", "banana", "mango"}
>
>print("mango" in fruits)
>```

**Output**

>```
>true
>```

## 🎥 YouTube

![youtube]()

<div style="display: flex; justify-content: space-between; margin-top: 30px;">
  <a
  href="python_chapter_12.0_python_set.md" style="text-decoration: none; font-weight: bold;">⬅️ Previous</a>
  <a 
  href="python_chapter_12.2_remove_set.md" style="text-decoration: none; font-weight: bold;">Next ➡️</a>
</div>
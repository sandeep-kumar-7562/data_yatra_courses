# 🔁 Loop tuple in python

Tuples are ordered collections, and you can access each element using loops. This chapter explains different ways to iterate through a tuple in Python.

___

## 📌 Using a `for` Loop

The most common way to loop through a tuple is by using a `for` loop.

> Example

>```python
>fruits = ("apple", "banana", "cherry")
>
>for i in fruits:
>    print(i)
>```

**Output**

>```
>apple
>banana
>cherry
>```

## 📌 Using a `for` Loop with Index (`range()` and `len()`)

If you need the index while looping, use `range()` and `len()`.

> Example

>```python
>fruits = ("apple", "banana", "cherry")
>
>for i in range(len(fruits)):
>   print(fruits[i])
>```

**Output**

>```
>apple
>banana
>cherry
>```

## 📌 Using a `while` Loop

A `while` loop can also be used to iterate over a tuple.

> Example

>```python
>fruits = ("apple", "banana", "cherry")
>i = 0
>
>while i < len(fruits):
>    print(fruits[i])
>    i += 1
>```

**Output**

>```
>apple
>banana
>cherry
>```

## YouTube

![youtube]()


<div style="display: flex; justify-content: space-between; margin-top: 30px;">
  <a
  href="python_chapter_11.3_pack_tuple.md" style="text-decoration: none; font-weight: bold;">⬅️ Previous</a>
  <a 
  href="python_chapter_11.5_join_tuple.md" style="text-decoration: none; font-weight: bold;">Next ➡️</a>
</div>

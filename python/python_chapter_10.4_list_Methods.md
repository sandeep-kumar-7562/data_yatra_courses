# 🧰 List Methods in Python

List methods are built-in functions in Python that help you add, remove, sort, or modify items in a list easily.

___

| Method      | Description                |
| ----------- | -------------------------- |
| `append()`  | Add single item at end     |
| `extend()`  | Add multiple items         |
| `insert()`  | Add item at specific index |
| `remove()`  | Remove first matching item |
| `pop()`     | Remove item by index       |
| `clear()`   | Remove all items           |
| `index()`   | Get index of item          |
| `count()`   | Count occurrences of item  |
| `sort()`    | Sort list in place         |
| `sorted()`  | Return sorted list         |
| `reverse()` | Reverse list               |
| `copy()`    | Copy list                  |


## 📌 1. `append()`

Adds a single item to the end of the list.

> Example

>```python
>fruits = ['apple', 'banana']
>
>fruits.append('orange')
>
>print(fruits)  
>```

**Output**

>```
>['apple', 'banana', 'orange']
>```

## 📌 2. `insert(index, item)`

Inserts an item at a specified position.

> Example

>```python
>fruits = ['apple', 'banana', 'orange']
>
>fruits.insert(1, 'grape')
>
>print(fruits)  
>```

**Output

>```
>['apple', 'grape', 'banana', 'orange']
>```

## 📌 3. `extend(iterable)`

Adds multiple items to the end of the list.

> Example

>```python
>fruits = ['apple', 'grape', 'banana', 'orange']
>
>fruits.extend(['cherry', 'mango'])
>
>print(fruits)  # ['apple', 'grape', 'banana', 'orange', 'cherry', 'mango']
>```

**Output

>```
> ['apple', 'grape', 'banana', 'orange', 'cherry', 'mango']
>```

## 📌 4. `remove(item)`

Removes the first occurrence of the item.

> Example

>```python
>fruits =  ['apple', 'grape', 'banana', 'orange', 'cherry', 'mango']
>
>fruits.remove('banana')
>
>print(fruits)  # ['apple', 'grape', 'orange', 'cherry', 'mango']
>```

**Output**

>```
>['apple', 'grape', 'orange', 'cherry', 'mango']
>```

## 🎥 YouTube

![youtube]()

<div style="display: flex; justify-content: space-between; margin-top: 30px;">
  <a
  href="python_chapter_10.3_list_Comprehension.md" style="text-decoration: none; font-weight: bold;">⬅️ Previous</a>
  <a 
  href="python_chapter_11_python_tuple.md" style="text-decoration: none; font-weight: bold;">Next ➡️</a>
</div>

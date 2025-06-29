## 🧾 Definition
A **`for loop`** in Python is used to **iterate over a sequence** (like a list, string, tuple, or range) and execute a block of code for each item in the sequence. It is ideal when the **number of iterations is known** or determined by the size of a collection.

## 🧩 Features
- Iterates over any **iterable**: strings, lists, tuples, ranges, dictionaries, etc.
- Automatically handles **loop counters**.
- Supports `[[break]]`, `[[continue]]`, and optional `[[else]]` clauses.
- Often combined with `[[range()]]` for numeric loops.

## 🧪 Examples

### ▶️ Basic For Loop
```python
for i in range(5):
    print(i)
# Output: 0 1 2 3 4
```

### ▶️ Iterating Over a String
```python
for letter in "Python":
    print(letter)
```

### ▶️ Iterating Over a List
```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

### ▶️ Using Break
```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

### ▶️ Using Continue
```python
for i in range(5):
    if i == 2:
        continue
    print(i)
```

### ▶️ For-Else Loop
```python
for i in range(3):
    print(i)
else:
    print("Loop completed")
```

## 🧠 Tip
- Use `enumerate()` to get index and value:
```python
for index, item in enumerate(["a", "b", "c"]):
    print(index, item)
```

- You can also loop over dictionaries with `.items()`:
```python
person = {"name": "Aarush", "age": 17}
for key, value in person.items():
    print(f"{key} = {value}")
```

## 🔗 Related
- [[while loops]]
- [[break]]
- [[continue]]
- [[else]]
- [[range()]]
- [[input]]
- [[loop control]]
- [[iteration]]
## 🧾 Definition
The **`print()`** function in Python is used to **display output** on the screen. It sends the specified message or value to the **standard output device** (usually the terminal or console). It is one of the most commonly used **[[built-in functions]]** in Python.

## 🧩 Features
- Can print **strings**, **numbers**, **variables**, **expressions**, etc.
- Supports **multiple arguments** separated by commas.
- Adds a **newline (`\n`)** at the end by default, unless changed using `end`.
- Allows customizing the **separator** between printed items using `sep`.
- Works in both **interactive** and **script** modes.

## 🧪 Examples

### ▶️ Basic Usage
```python
print("Hello, world!")
```

### ▶️ Printing Multiple Items
```python
print("Name:", "Aarush", "Age:", 17)
# Output: Name: Aarush Age: 17
```

### ▶️ Using `sep` and `end`
```python
print("2025", "06", "29", sep="-")
# Output: 2025-06-29

print("Loading", end="...")
print("Done")
# Output: Loading...Done
```

### ▶️ Printing Variables
```python
name = "Aarush"
print("Hello", name)
```

### ▶️ With Escape Sequences
```python
print("Line1\nLine2\tTabbed")
```

### ▶️ Colored Text (with ANSI codes)
```python
print("\033[31mThis is red text.\033[0m")
```

## 🧠 Tip
- In Python 2, `print` was a statement: `print "text"`  
  In Python 3, it's a function: `print("text")`

- To output to a file:
```python
with open("log.txt", "w") as f:
    print("Logging...", file=f)
```

- You can use `f-strings` to embed expressions:
```python
name = "Aarush"
print(f"Welcome, {name}!")
```

## 🔗 Related
- [[input]]
- [[variables]]
- [[f-string]]
- [[escape sequences]]
- [[data types]]
- [[built-in functions]]

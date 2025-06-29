## 🧾 Definition
**Concatenation** is the process of **joining strings together** to form a new string. In Python, strings can be concatenated using the `+` operator or with **[[f-string]]** and the `,` separator inside `[[print]]`.

## 🧩 Features
- Only works with **strings**; you must convert numbers using `str()`.
- Can use `+`, `+=`, or `f-strings` for dynamic insertion.
- Useful for forming messages, prompts, and combined outputs.

## 🧪 Examples

### ▶️ Basic Concatenation
```python
first = "Hello"
second = "World"
result = first + " " + second
print(result)  # Output: Hello World
```

### ▶️ With Non-String Values
```python
name = "Aarush"
age = 17
print("Name: " + name + ", Age: " + str(age))
```

### ▶️ Using `+=`
```python
msg = "Python"
msg += " is awesome!"
print(msg)
```

### ▶️ Alternative: Using Commas in `print()`
```python
print("Age:", 17)  # Automatically adds space
```

### ▶️ Using `f-string` (Recommended)
```python
name = "Aarush"
print(f"Hello, {name}")
```

## 🧠 Tip
- Prefer `f-strings` for readability and performance.
- Avoid using `+` for many strings inside loops — it’s inefficient.

## 🔗 Related
- [[print]]
- [[f-string]]
- [[type conversion]]
- [[data types]]
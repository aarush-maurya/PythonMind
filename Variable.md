## 🧾 Definition
A **variable** in Python is a **named reference to a value** stored in memory. It allows you to store, retrieve, and manipulate data. Variables act as **labels** pointing to values of various **[[data types]]**.

## 🧩 Features
- No need to declare the type; Python is **dynamically typed**.
- Variable names are **case-sensitive**.
- Must start with a **letter or underscore**, and can contain letters, digits, or underscores.
- Follows **snake_case** naming convention (e.g., `total_amount`).
- Can be reassigned or updated at any time.

## 🧪 Examples

### ▶️ Basic Assignment
```python
name = "Aarush"
age = 17
```

### ▶️ Dynamic Typing
```python
x = 10      # integer
x = "ten"   # now a string
```

### ▶️ Multiple Assignment
```python
a, b, c = 1, 2, 3
```

### ▶️ Swapping Variables
```python
x, y = 5, 10
x, y = y, x
```

### ▶️ With Expressions
```python
price = 100
tax = 0.18
total = price + price * tax
```

## 🧠 Tip
- Use meaningful names: `score` is better than `s`.
- Avoid using reserved words like `print`, `input`, `if`, etc.  
  See: [[keywords]]

## 🔗 Related
- [[data types]]
- [[assignment]]
- [[constants]]
- [[naming conventions]]
- [[keywords]]
- [[print]]
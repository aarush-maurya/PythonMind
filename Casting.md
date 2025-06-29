## 🧾 Definition
**Casting** (also called **type conversion**) in Python refers to **converting a value from one data type to another** using built-in conversion functions. It's commonly used when dealing with `[[input]]`, mathematical operations, and string formatting.

## 🧩 Features
- Converts between `[[data types]]` like `str`, `int`, `float`, `bool`.
- Can be **explicit** (manual) or **implicit** (automatic).
- Prevents type mismatch errors, especially when using `[[input]]` (which returns strings).
- Casting incompatible types raises `ValueError`.

## 🧪 Examples

### ▶️ Basic Casting
```python
x = "10"
y = int(x)  # Converts string to integer
```

### ▶️ Common Conversion Functions
```python
str(123)      # → "123"
int("456")    # → 456
float("3.14") # → 3.14
bool(0)       # → False
```

### ▶️ Input Example
```python
age = int(input("Enter your age: "))
print(age + 1)
```

### ▶️ Float to Int (loses decimals)
```python
x = 5.99
print(int(x))  # Output: 5
```

### ▶️ Invalid Casting (Error)
```python
int("hello")  # Raises ValueError
```

## 🧠 Tip
- Casting helps when combining different types in operations.
- Use `type()` to check data type before/after casting:
```python
print(type(str(100)))  # <class 'str'>
```

## 🔗 Related
- [[data types]]
- [[input]]
- [[type()]]
- [[print]]
- [[f-string]]
- [[errors]]
- [[ValueError]]
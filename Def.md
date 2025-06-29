## 🧾 Definition
The keyword **`def`** is used in Python to **define a function**. Functions are **reusable blocks of code** that perform a specific task and can be called multiple times with different inputs.

## 🧩 Features
- Begins a **function definition**.
- Always followed by:
  - a **function name**
  - parentheses `()` (may contain `[[parameters]]`)
  - a colon `:`
- The indented block below `def` is the **function body**.
- Can include `[[return]]` statements.
- May be called before or after definition (depending on context).

## 🧪 Examples

### ▶️ Basic Function Definition
```python
def greet():
    print("Hello, world!")
greet()
```

### ▶️ Function with Parameters
```python
def add(x, y):
    return x + y
print(add(3, 5))  # Output: 8
```

### ▶️ Function with Default Parameter
```python
def greet(name="Guest"):
    print(f"Hello, {name}")
greet()            # Output: Hello, Guest
greet("Aarush")    # Output: Hello, Aarush
```

### ▶️ Function with Return Value
```python
def square(n):
    return n * n
result = square(4)
print(result)  # Output: 16
```

## 🧠 Tip
- Function names should follow `[[naming conventions]]` (snake_case).
- Use `[[docstrings]]` right after `def` to document the function.

## 🔗 Related
- [[functions]]
- [[parameters]]
- [[return]]
- [[print]]
- [[input]]
- [[docstrings]]
- [[naming conventions]]
- [[scope]]
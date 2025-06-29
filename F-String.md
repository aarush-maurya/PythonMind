## 🧾 Definition
An **f-string** (formatted string literal) is a way to embed **expressions and variables** directly inside string literals using curly braces `{}`. Introduced in Python 3.6, it makes string formatting **concise**, **readable**, and **efficient**.

## 🧩 Features
- Begin the string with `f` or `F` before the opening quote.
- Expressions inside `{}` are evaluated at runtime.
- Supports:
  - Variables
  - Arithmetic
  - Function calls
  - Inline formatting (`:.2f`, `:>10`, etc.)
- Faster and cleaner than `[[concatenation]]` or `[[format()]]`.

## 🧪 Examples

### ▶️ Basic Usage
```python
name = "Aarush"
print(f"Hello, {name}!")
```

### ▶️ Expressions Inside
```python
x = 5
y = 10
print(f"Sum: {x + y}")
```

### ▶️ Function Calls in Place
```python
def greet():
    return "Hi"
print(f"{greet()}, user.")
```

### ▶️ Formatting Numbers
```python
pi = 3.1415926
print(f"Pi: {pi:.2f}")       # Output: Pi: 3.14
print(f"{42:>5}")            # Output: '   42' (right-aligned)
print(f"{42:<5}")            # Output: '42   ' (left-aligned)
```

### ▶️ Nesting in Long Strings
```python
user = "admin"
role = "moderator"
print(f"User: {user}, Role: {role.upper()}")
```

## 🧠 Tip
- Avoid using f-strings in Python versions earlier than 3.6.
- Curly braces can be escaped using double braces:
```python
print(f"{{Hello}}")  # Output: {Hello}
```

## 🔗 Related
- [[print]]
- [[variables]]
- [[data types]]
- [[functions]]
- [[format()]]
- [[concatenation]]
- [[string formatting]]
- [[python 3.6]]
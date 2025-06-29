## 🧾 Definition
A **comment** is a piece of text in a Python program that is **ignored by the interpreter**. It is used to explain code, improve readability, or temporarily disable code during debugging. Comments are not executed and have no effect on the program’s output.

## 🧩 Features
- **Single-line comments** start with a `#` symbol.
- **Multi-line comments** can be created using:
  - Multiple `#` symbols on each line, or
  - Triple quotes (`'''` or `"""`) — although these are technically **[[docstrings]]**, not true comments.
- Useful for:
  - Describing logic
  - Clarifying complex code
  - Marking TODOs or fixes
  - Debugging by disabling code temporarily

## 🧪 Examples

### ▶️ Single-line Comment
```python
# This is a comment
print("Hello")  # This prints a greeting
```

### ▶️ Multi-line Comments (Informal)
```python
# This is line 1
# This is line 2
# This is line 3
```

### ▶️ Using Triple Quotes (Not Recommended for Comments)
```python
'''
This looks like a comment,
but it's actually a multi-line string
that is not assigned to any variable.
'''
```

## 🧠 Tip
- Comments improve **[[code readability]]** and maintainability.
- Keep comments **short, relevant, and up-to-date**.
- Avoid redundant comments like:
```python
i = 0  # Set i to 0  ← not useful
```

## 🔗 Related
- [[syntax]]
- [[docstrings]]
- [[debugging]]
- [[readability]]
- [[good coding practices]]
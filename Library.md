## 🧾 Definition
A **library** in Python is a **collection of pre-written code (modules and packages)** that provides **functions, classes, and tools** to solve common problems or extend the language’s functionality without writing everything from scratch.

Libraries can be:
- **Standard** (built into Python)
- **Third-party** (installable via `[[pip]]`)
- **Custom/user-defined**

## 🧩 Features
- Promotes **code reuse** and **abstraction**.
- Can include one or many **[[modules]]**.
- Accessed using the `[[import]]` keyword.
- Can be used for:
  - Math (`[[math]]`)
  - Web requests (`requests`)
  - Machine learning (`scikit-learn`, `tensorflow`)
  - GUI (`tkinter`, `customtkinter`)
  - And much more.

## 🧪 Examples

### ▶️ Using a Standard Library
```python
import math
print(math.sqrt(16))  # Output: 4.0
```

### ▶️ Using a Specific Function from a Library
```python
from math import pi
print(pi)
```

### ▶️ Installing and Using a Third-Party Library
```bash
pip install requests
```

```python
import requests
response = requests.get("https://example.com")
print(response.status_code)
```

### ▶️ Creating Your Own Library
```python
# mylib.py
def greet(name):
    return f"Hello, {name}!"
```

```python
# main.py
import mylib
print(mylib.greet("Aarush"))
```

## 🧠 Tip
- Use `dir(library)` to explore what's inside a library.
- Use `help(library)` for documentation.
- Popular sources: `pypi.org`, GitHub, documentation pages.

## 🔗 Related
- [[module]]
- [[package]]
- [[import]]
- [[pip]]
- [[math]]
- [[requests]]
- [[standard library]]
- [[third-party libraries]]
- [[custom libraries]]
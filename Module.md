
## 🧾 Definition
A **module** in Python is a `.py` file that contains Python code—such as variables, functions, or classes—that can be **imported and reused** in other Python programs. It helps organize code and promotes **modularity and maintainability**.

## 🧩 Features
- Helps **reuse code** across multiple programs.
- Every module runs in its own **namespace**.
- Can include:
  - Variables
  - Functions
  - Classes
  - Executable statements
- Types:
  - **Built-in modules** (e.g., `math`, `random`)
  - **User-defined modules**
  - **External modules** (e.g., `requests`, `numpy`)
- Can import in two ways:
  - `import module_name`
  - `from module_name import something`

## 🧪 Examples

### ▶️ Built-in Module
```python
import math
print(math.sqrt(16))  # Output: 4.0
```

### ▶️ User-defined Module

**greetings.py**
```python
def welcome(name):
    return f"Hello, {name}!"
```

**main.py**
```python
import greetings
print(greetings.welcome("Aarush"))
```

### ▶️ External Module (needs installation)
```python
import requests
response = requests.get("https://example.com")
print(response.status_code)
```

## 🧠 Tip
- To see available functions in a module:
```python
import math
print(dir(math))
```

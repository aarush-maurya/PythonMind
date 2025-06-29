## 🧾 Definition
**Data types** define the **type of data** a variable or expression holds. Each value in Python belongs to a **specific type**, which determines what operations can be performed on it and how it is stored in memory.

## 🧩 Categories

### 🔹 Primitive Data Types
- `int` – Integer numbers  
- `float` – Decimal numbers  
- `str` – Strings (text)  
- `bool` – Boolean (`True` or `False`)  
- `NoneType` – Represents no value (`[[None]]`)

### 🔹 Collection Data Types
- `list` – Ordered, mutable sequences  
- `tuple` – Ordered, immutable sequences  
- `set` – Unordered, unique elements  
- `dict` – Key-value pairs (dictionary)

### 🔹 Other Types
- `complex` – Complex numbers (`3 + 4j`)
- `range` – Used for sequences of numbers, often in `[[for loops]]`
- `bytes`, `bytearray`, `memoryview` – Binary data types

## 🧪 Examples

### ▶️ Primitive Types
```python
x = 10            # int
y = 3.14          # float
name = "Aarush"   # str
flag = True       # bool
nothing = None    # NoneType
```

### ▶️ Collection Types
```python
nums = [1, 2, 3]                # list
coords = (10.0, 20.0)          # tuple
unique_vals = {1, 2, 3}        # set
profile = {"name": "Aarush"}   # dict
```

### ▶️ Checking Type
```python
print(type(42))      # <class 'int'>
print(type([1, 2]))  # <class 'list'>
```

## 🧠 Tip
- Use `type()` to inspect a variable's type.
- Use `[[casting]]` to convert between data types (e.g., `str()`, `int()`).
- Know the **mutability**:
  - `list`, `dict`, `set` → mutable  
  - `str`, `tuple`, `int`, `float` → immutable

## 🔗 Related
- [[variable]]
- [[casting]]
- [[type()]]
- [[list]]
- [[tuple]]
- [[set]]
- [[dictionary]]
- [[None]]
- [[for loops]]
- [[input]]
- [[boolean values]]
- [[mutability]]
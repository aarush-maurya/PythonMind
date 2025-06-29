## 🧾 Definition
**`elif`** (short for **“else if”**) is used in Python to check **multiple conditions** after an initial `[[if]]` statement. It allows the program to execute the first `True` condition and skip the rest.

## 🧩 Features
- Appears **after `if`** and **before `[[else]]`** (if present).
- You can use **multiple `elif` blocks** in a single condition chain.
- Conditions are checked **in order**; only the **first `True` block** executes.
- Makes **multi-branch logic** clearer and more efficient than nested `if` statements.

## 🧪 Examples

### ▶️ If-Elif-Else
```python
temp = 25
if temp > 30:
    print("Hot")
elif temp >= 20:
    print("Warm")
else:
    print("Cool")
```

### ▶️ Multiple Elif
```python
marks = 78
if marks >= 90:
    print("Grade: A")
elif marks >= 80:
    print("Grade: B")
elif marks >= 70:
    print("Grade: C")
else:
    print("Grade: D")
```

## 🧠 Tip
- The flow stops at the **first `True` condition** — remaining blocks are skipped.
- `elif` must always follow an `if`; it cannot stand alone.

## 🔗 Related
- [[if]]
- [[else]]
- [[control flow]]
- [[comparison operators]]
- [[syntax rules]]
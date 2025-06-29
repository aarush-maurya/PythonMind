## 🧾 Definition
**Nesting** in Python refers to placing one **code block** inside another, such as an `[[if]]` inside another `if`, or a `[[loop]]` inside another loop. This allows for **layered decision making** and **hierarchical logic**.

## 🧩 Features
- Commonly used with:
  - `[[if]]`, `[[elif]]`, `[[else]]` blocks
  - `[[for loops]]` and `[[while loops]]`
  - `[[functions]]`
- Python uses **indentation** to define nested blocks.
- Nesting can go multiple levels deep, but excessive nesting reduces **[[readability]]** and should be avoided.

## 🧪 Examples

### ▶️ Nested If
```python
num = 10
if num > 0:
    if num % 2 == 0:
        print("Positive even number")
    else:
        print("Positive odd number")
```

### ▶️ Nested Loops
```python
for i in range(3):
    for j in range(2):
        print(f"i={i}, j={j}")
```

### ▶️ Nested If in Loops
```python
for num in range(1, 6):
    if num % 2 == 0:
        print(f"{num} is even")
    else:
        print(f"{num} is odd")
```

### ▶️ Nested Function Calls (conceptual nesting)
```python
def outer():
    def inner():
        print("Inner function")
    print("Outer function")
    inner()
outer()
```

## 🧠 Tip
- Nesting is powerful but should be **used with care**.
- Refactor deeply nested code into **[[functions]]** or **[[logical blocks]]** to improve clarity.

## 🔗 Related
- [[if]]
- [[else]]
- [[elif]]
- [[for loops]]
- [[while loops]]
- [[functions]]
- [[readability]]
- [[logical blocks]]
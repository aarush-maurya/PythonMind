## 🧾 Definition
The **`if` statement** in Python is used for **decision making**. It allows the program to **execute a block of code** only if a specified condition evaluates to `True`.

## 🧩 Features
- Evaluates a **Boolean condition** using comparison or logical operators.
- Can include optional `[[elif]]` and `[[else]]` branches.
- Supports **nested if-statements** for multi-layered logic.
- Often used in **[[control flow]]**, **[[user input]]**, and **[[loops]]**.

## 🧪 Examples

### ▶️ Basic If Statement
```python
x = 10
if x > 5:
    print("x is greater than 5")
```

### ▶️ If-Else
```python
age = int(input("Enter age: "))
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

### ▶️ If-Elif-Else
```python
score = 85
if score >= 90:
    print("Grade: A")
elif score >= 75:
    print("Grade: B")
else:
    print("Grade: C")
```

### ▶️ Nested If
```python
x = 10
if x > 0:
    if x % 2 == 0:
        print("Positive even number")
```

## 🧠 Tip
- Use **indentation (tabs/spaces)** correctly; Python is indentation-sensitive.
- Conditions can include:
  - `==`, `!=`, `>`, `<`, `>=`, `<=`
  - Logical operators: `and`, `or`, `not`

- Use `bool()` to understand truthy/falsy values.  
  See: [[boolean values]]

## 🔗 Related
- [[elif]]
- [[else]]
- [[control flow]]
- [[boolean values]]
- [[comparison operators]]
- [[logical operators]]
- [[user input]]
- [[loops]]
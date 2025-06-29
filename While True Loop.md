## 🧾 Definition
A **`while True` loop** is a type of infinite `[[while loop]]` that keeps running **forever** unless it is **manually broken** using `[[break]]`. It is commonly used for **continuous programs**, **[[menu-driven programs]]**, **[[event loops]]**, and **input validation**.

## 🧩 Features
- The condition `True` is always truthy, so the loop runs infinitely.
- Must include a `[[break]]` statement (or some exit logic) to stop execution.
- Often used when **you don’t know when the loop should end** at the start.
- Highly useful in **CLI apps**, **games**, and **servers**.

## 🧪 Examples

### ▶️ Basic While True Loop
```python
while True:
    print("Running...")
    break  # Prevents infinite loop in this case
```

### ▶️ Menu-Driven Example
```python
while True:
    print("1. Add\n2. Subtract\n3. Exit")
    choice = input("Enter choice: ")
    if choice == "3":
        print("Exiting...")
        break
```

### ▶️ Password Retry Example
```python
while True:
    pwd = input("Enter password: ")
    if pwd == "admin123":
        print("Access granted.")
        break
    else:
        print("Wrong password, try again.")
```

### ▶️ Controlled Infinite Loop
```python
counter = 0
while True:
    counter += 1
    print("Tick", counter)
    if counter == 5:
        break
```

## 🧠 Tip
- Without `break`, `while True` will **never stop**—use it wisely.
- Often combined with `[[input]]`, `[[if]]`, and `[[elif]]` to create **interactive** or **repetitive** logic blocks.

## 🔗 Related
- [[while loop]]
- [[break]]
- [[input]]
- [[if]]
- [[elif]]
- [[menu-driven programs]]
- [[infinite loop]]
- [[event loop]]
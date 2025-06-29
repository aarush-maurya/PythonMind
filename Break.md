## 🧾 Definition
The **`break`** statement in Python is used to **exit a loop prematurely** when a specific condition is met. It can be used inside both `[[for loops]]` and `[[while loops]]`, including `[[while True loop]]`.

## 🧩 Features
- Immediately **terminates the nearest enclosing loop**.
- Skips any remaining iterations and resumes execution **after the loop**.
- Often used with `[[if]]` or `[[elif]]` to create conditional exits.
- Used to stop infinite loops like `while True`.

## 🧪 Examples

### ▶️ Break in While Loop
```python
i = 0
while i < 10:
    if i == 5:
        break
    print(i)
    i += 1
```

### ▶️ Break in For Loop
```python
for char in "hello":
    if char == "l":
        break
    print(char)
```

### ▶️ While True Loop with Break
```python
while True:
    cmd = input("Enter command: ")
    if cmd == "exit":
        break
    print("Running...")
```

### ▶️ Break Nested in If
```python
x = 0
while x < 10:
    if x == 3:
        print("Breaking loop")
        break
    x += 1
```

## 🧠 Tip
- Use `break` to escape infinite or menu loops.
- In a `[[loop else]]` block, if `break` is executed, the `else` part **will not run**.

## 🔗 Related
- [[while loops]]
- [[while True loop]]
- [[for loops]]
- [[if]]
- [[elif]]
- [[else]]
- [[loop else]]
- [[input]]
- [[menu-driven programs]]
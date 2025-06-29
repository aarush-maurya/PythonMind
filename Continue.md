
## 🧾 Definition
The **`continue`** statement in Python is used inside loops to **skip the current iteration** and **move directly to the next one**, without executing the remaining code in the loop body for that iteration.

## 🧩 Features
- Can be used in both `[[for loops]]` and `[[while loops]]`.
- Typically combined with `[[if]]` or `[[elif]]` conditions.
- Does **not exit** the loop like `[[break]]`; it just skips forward.
- Often used in **[[input validation]]**, **[[filters]]**, and **skipping unwanted data**.

## 🧪 Examples

### ▶️ Continue in For Loop
```python
for i in range(5):
    if i == 2:
        continue
    print(i)
# Skips printing 2
```

### ▶️ Continue in While Loop
```python
i = 0
while i < 5:
    i += 1
    if i == 3:
        continue
    print(i)
# Skips printing 3
```

### ▶️ Skip Empty Input
```python
while True:
    data = input("Enter something: ")
    if data == "":
        continue
    if data == "exit":
        break
    print("You entered:", data)
```

## 🧠 Tip
- Be careful with `continue` inside `[[while loops]]` — make sure loop control (like `i += 1`) isn't skipped, or you'll create an **infinite loop**.
- Useful when you want to **ignore specific cases** without ending the loop.

## 🔗 Related
- [[break]]
- [[while loops]]
- [[for loops]]
- [[if]]
- [[elif]]
- [[input]]
- [[loop control]]
- [[infinite loop]]
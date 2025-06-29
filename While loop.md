## 🧾 Definition
A **`while` loop** in Python repeatedly executes a block of code **as long as a given condition is `True`**. It is used when the number of iterations is **not known in advance** and depends on a condition.

## 🧩 Features
- Checks the condition **before** executing the loop body.
- Can run indefinitely if the condition never becomes `False`.
- Supports `[[break]]`, `[[continue]]`, and `[[else]]` clauses.
- Ideal for **[[input]] validation**, **[[menu-driven programs]]**, and **[[event-driven loops]]**.

## 🧪 Examples

### ▶️ Basic While Loop
```python
count = 0
while count < 5:
    print("Count:", count)
    count += 1
```

### ▶️ Infinite Loop
```python
while True:
    print("This runs forever")
    break  # Use break to exit
```

### ▶️ Using Else with While
```python
x = 0
while x < 3:
    print(x)
    x += 1
else:
    print("Loop finished")
```

### ▶️ Input Validation Example
```python
user_input = ""
while user_input != "exit":
    user_input = input("Type 'exit' to quit: ")
```

### ▶️ With Continue and Break
```python
i = 0
while i < 5:
    i += 1
    if i == 3:
        continue  # Skip this iteration
    if i == 4:
        break     # Exit the loop
    print(i)
```

## 🧠 Tip
- Ensure your loop condition **eventually becomes false** to avoid infinite loops.
- Combine with flags or counters for controlled termination.

## 🔗 Related
- [[for loops]]
- [[break]]
- [[continue]]
- [[else]]
- [[input]]
- [[conditional statements]]
- [[menu-driven programs]]
- [[control flow]]
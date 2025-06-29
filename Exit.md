## 🧾 Definition
**`exit()`**, `quit()`, and `sys.exit()` are used in Python to **terminate a program** before it reaches the end of the script. They are commonly used to **break out of loops**, **end programs**, or **handle errors** gracefully.

## 🧩 Features
- `exit()` and `quit()` are **built-in** functions from the `site` module, mainly used in **interactive mode** (like IDLE or terminal).
- `sys.exit()` is more **reliable for scripts**, and allows **exit codes**.
- Often used with `[[while True loop]]` or in **[[menu-driven programs]]** to provide an exit option.

## 🧪 Examples

### ▶️ Using `exit()` (Simple)
```python
print("Starting...")
exit()
print("This will not run")
```

### ▶️ Using `sys.exit()` (Recommended for scripts)
```python
import sys
age = int(input("Enter your age: "))
if age < 0:
    print("Invalid age")
    sys.exit()
print("Proceeding...")
```

### ▶️ Exit with Code
```python
import sys
sys.exit(1)  # 0 = normal exit, any other number = error
```

### ▶️ With `while True`
```python
while True:
    cmd = input("Type 'exit' to quit: ")
    if cmd == "exit":
        print("Exiting...")
        break  # or use exit()
```

## 🧠 Tip
- `exit()` and `quit()` should be avoided in production scripts — use `sys.exit()` instead.
- You can catch `SystemExit` exceptions if needed:
```python
try:
    sys.exit()
except SystemExit:
    print("Caught exit")
```

## 🔗 Related
- [[while True loop]]
- [[break]]
- [[input]]
- [[menu-driven programs]]
- [[error handling]]
- [[SystemExit]]
- [[sys module]]
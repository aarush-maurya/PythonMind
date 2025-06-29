## 🧾 Definition
The **`input()`** function in Python is used to **take user input** from the console. It reads a line of text typed by the user and returns it as a **string**. It's a key component of **interactive programs**.

## 🧩 Features
- Always returns **string data**, even if the user types a number.
- You can pass a **prompt** inside the parentheses.
- Combine with `int()` or `float()` to convert input to other **[[data types]]**.
- Useful in **[[control flow]]**, loops, and interactive apps.

## 🧪 Examples

### ▶️ Basic Input
```python
name = input("Enter your name: ")
print("Hello,", name)
```

### ▶️ Converting to Integer
```python
age = int(input("Enter your age: "))
print("You will be", age + 1, "next year.")
```

### ▶️ Multiple Inputs
```python
x = input("Enter x: ")
y = input("Enter y: ")
print("Sum:", int(x) + int(y))
```

### ▶️ Inline Prompt with f-strings
```python
username = input(f"What is your username? ")
print(f"Welcome, {username}!")
```

## 🧠 Tip
- Always **validate** input using `try-except` or conditionals.
- To take multiple values in one line:
```python
a, b = input("Enter two values: ").split()
```

- Combine with `print()` for user-friendly interaction.  
  See: [[print]]

## 🔗 Related
- [[print]]
- [[type conversion]]
- [[data types]]
- [[control flow]]
- [[f-string]]
- [[functions]]
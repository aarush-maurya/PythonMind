## 🧾 Definition
The **`return`** statement in Python is used inside a `[[function]]` to **send a value back** to the place where the function was called. It **terminates the function’s execution** and optionally passes back a result.

## 🧩 Features
- Ends the current function call.
- Can return:
  - A **single value**
  - Multiple values (as a **tuple**)
  - Nothing (i.e., `None`)
- After `return`, the function **immediately exits**.
- Without a `return`, functions return `None` by default.

## 🧪 Examples

### ▶️ Returning a Value
```python
def square(x):
    return x * x

print(square(4))  # Output: 16
```

### ▶️ Returning Multiple Values
```python
def divide_and_remainder(a, b):
    return a // b, a % b

q, r = divide_and_remainder(10, 3)
print(q, r)  # Output: 3 1
```

### ▶️ Returning None
```python
def no_return():
    print("This has no return")

result = no_return()
print(result)  # Output: None
```

### ▶️ Early Exit Using Return
```python
def is_even(n):
    if n % 2 == 0:
        return True
    return False
```

## 🧠 Tip
- You can return complex objects like `[[lists]]`, `[[dictionaries]]`, or even other `[[functions]]`.
- Returning early using `return` makes code **clear and efficient**.

## 🔗 Related
- [[function]]
- [[def]]
- [[None]]
- [[print]]
- [[tuple]]
- [[list]]
- [[dictionary]]
- [[scope]]
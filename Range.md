## 🧾 Definition
**`range()`** is a built-in Python function that returns a **sequence of numbers**, commonly used in `[[for loops]]` to control iteration. It does **not generate a list** immediately but returns a **range object** which is iterable.

## 🧩 Features
- Can take **1, 2, or 3 arguments**:
  - `range(stop)`
  - `range(start, stop)`
  - `range(start, stop, step)`
- The sequence is:
  - **inclusive of `start`**
  - **exclusive of `stop`**
- Step can be **positive** or **negative**.

## 🧪 Examples

### ▶️ Range with One Argument
```python
for i in range(5):
    print(i)
# Output: 0 1 2 3 4
```

### ▶️ Range with Start and Stop
```python
for i in range(2, 6):
    print(i)
# Output: 2 3 4 5
```

### ▶️ Range with Step
```python
for i in range(0, 10, 2):
    print(i)
# Output: 0 2 4 6 8
```

### ▶️ Range with Negative Step
```python
for i in range(5, 0, -1):
    print(i)
# Output: 5 4 3 2 1
```

### ▶️ Convert to List
```python
nums = list(range(5))
print(nums)
# Output: [0, 1, 2, 3, 4]
```

## 🧠 Tip
- `range()` is memory efficient because it **generates values lazily**.
- If you need the values immediately, convert it to a list using `list(range(...))`.

## 🔗 Related
- [[for loops]]
- [[iteration]]
- [[list]]
- [[built-in functions]]
- [[loop control]]
- [[step size]]
- [[start and stop]]
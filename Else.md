## 🧾 Definition
The **`else` statement** in Python is used as the **default branch** of an `[[if]]` or `[[elif]]` structure. It executes a block of code **when none of the previous conditions are `True`**.

## 🧩 Features
- Always appears **after** all `[[if]]` and `[[elif]]` blocks.
- Does **not require a condition**—it catches everything not handled earlier.
- Works with **indentation** to define its scope.
- Must be aligned correctly with its corresponding `if` block.
- Used in both **[[conditional statements]]** and **[[loops]]** (like `for-else`, `while-else`).

## 🧪 Examples

### ▶️ If-Else
```python
x = int(input("Enter a number: "))
if x > 0:
    print("Positive")
else:
    print("Zero or Negative")
```

### ▶️ With Elif
```python
score = 55
if score >= 90:
    print("Grade A")
elif score >= 60:
    print("Grade B")
else:
    print("Grade C")
```

### ▶️ Else in a Loop
```python
for i in range(5):
    if i == 3:
        break
else:
    print("Loop completed without break")
```

## 🧠 Tip
- `else` without `if` will raise a `SyntaxError`.
- Loop `else` runs only if the loop **did not exit via `break`**.

## 🔗 Related
- [[if]]
- [[elif]]
- [[loops]]
- [[break]]
- [[conditional statements]]
- [[syntax rules]]
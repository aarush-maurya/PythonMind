# String Operation

## 🧾 Definition
**String operations** in Python refer to the various ways you can **manipulate, access, or transform string data**. Since strings are **sequences of characters**, they support indexing, slicing, and many built-in methods.

## 🧩 Features
- Strings are **immutable**.
- Can be combined with `[[f-string]]`, `[[concatenation]]`, and `[[casting]]`.
- Use `[[string methods]]` for transformation and checks.
- Support **indexing**, **slicing**, and **iteration** like other sequences.

## 🧪 Examples

### ▶️ Concatenation
```python
first = "Hello"
last = "World"
full = first + " " + last
print(full)  # Output: Hello World
```

### ▶️ Indexing and Slicing
```python
s = "Python"
print(s[0])    # Output: P
print(s[-1])   # Output: n
print(s[1:4])  # Output: yth
```

### ▶️ Case Methods
```python
s = "hello"
print(s.upper())  # Output: HELLO
print(s.capitalize())  # Output: Hello
```

### ▶️ Search and Replace
```python
text = "I like cats"
print(text.replace("cats", "dogs"))  # I like dogs
print("like" in text)  # True
```

### ▶️ Length and Stripping
```python
msg = "  spaced  "
print(len(msg))         # 10
print(msg.strip())      # 'spaced'
```

### ▶️ Iterating Through String
```python
for char in "hi":
    print(char)
```

## 🧠 Tip
- Strings are **immutable**, so operations return new strings.
- Use `dir(str)` or `help(str)` to explore all string methods.

## 🔗 Related
- [[f-string]]
- [[concatenation]]
- [[casting]]
- [[data types]]
- [[input]]
- [[string methods]]
- [[indexing]]
- [[slicing]]
- [[immutability]]
- [[for loops]]
- [[operators]]
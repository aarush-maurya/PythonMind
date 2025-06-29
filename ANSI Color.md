# 🧾 Definition
**ANSI escape codes** are special sequences of characters used to **control formatting and color** in terminal outputs. In Python, they are commonly used with `print()` to style text with **foreground (text)** and **background** colors.

These codes start with `\033[` (or `\x1b[`) followed by codes ending in `m`.

## 🧩 Features
- Control **text color**, **background color**, and **styles** (bold, underline).
- Works in most **Unix-based** terminals and some Windows terminals.
- Supports **standard (30–37)** and **bright (90–97)** colors.
- Backgrounds use **40–47** (standard) and **100–107** (bright).
- Can reset color using code `0`.

## 🧪 Examples

### ▶️ Basic Structure
```python
print("\033[31mRed Text\033[0m")
```
Format: `\033[<style>;<FG>;<BG>m`

### ▶️ Foreground Color Codes

| Color     | Code | Bright Code |
|-----------|------|-------------|
| Black     | 30   | 90          |
| Red       | 31   | 91          |
| Green     | 32   | 92          |
| Yellow    | 33   | 93          |
| Blue      | 34   | 94          |
| Magenta   | 35   | 95          |
| Cyan      | 36   | 96          |
| White     | 37   | 97          |

### ▶️ Background Color Codes

| Color     | Code | Bright Code |
|-----------|------|-------------|
| Black     | 40   | 100         |
| Red       | 41   | 101         |
| Green     | 42   | 102         |
| Yellow    | 43   | 103         |
| Blue      | 44   | 104         |
| Magenta   | 45   | 105         |
| Cyan      | 46   | 106         |
| White     | 47   | 107         |

### ▶️ Reset and Style Codes

| Style         | Code |
|---------------|------|
| Reset         | 0    |
| Bold          | 1    |
| Underline     | 4    |
| Reversed      | 7    |

## 🧪 Code Samples

### ▶️ Red Foreground
```python
print("\033[31mThis is red\033[0m")
```

### ▶️ Green Background + White Foreground
```python
print("\033[37;42mWhite on Green\033[0m")
```

### ▶️ Bold Yellow Text
```python
print("\033[1;33mBold Yellow\033[0m")
```

### ▶️ Bright Cyan Text on Bright Red Background
```python
print("\033[96;101mCyan on Red\033[0m")
```

### ▶️ Using variables for color
```python
RED = "\033[31m"
RESET = "\033[0m"
print(RED + "Alert!" + RESET)
```

## 🧠 Tip
- Always end colored output with `\033[0m` to **reset styling**.
- You can combine codes using semicolons, e.g., `1;31` for bold red.
- Not all terminals support bright codes; test before deploying.

## 🔗 Related
- [[print]]
- [[escape sequences]]
- [[terminal]]
- [[formatting text]]
- [[debugging]]
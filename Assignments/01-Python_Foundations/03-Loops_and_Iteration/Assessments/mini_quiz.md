# ❓ Mini Quiz: 04 - Loops and Iteration

--- Jose Espino

### 1. What does `range(3, 8)` generate?

---it generats the numbers starting with 3 unto 8 - 1 (7)

### 2. Which keyword skips the rest of the loop and moves to the next iteration?

---continue

### 3. What keyword stops a loop early?

---break

### 4. What does this print?

```python
for i in range(3):
    print("Loop:", i)
```

---Loop: 0
    Loop: 1
    Loop: 2

### 5. What is the correct way to open a file named `data.txt` for reading using `with`?

with ('practice.txt', 'r') as f:
    for lines in f:
        print(lines.strip())
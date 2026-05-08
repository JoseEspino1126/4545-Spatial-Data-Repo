# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` <class 'int'>

2. What scalar type would best represent:
   - A person's name: string
   - Their age: int

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
# Example: an int, float, str, and bool

x = 10
name = "jose"
height = "5.6"
tall = True
print(x, type(x))
print(name, type(name))
print(height, type(name))
print(tall, type(tall))
```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` it means does not equal

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` true

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
# Your code:
if grade >= 70:
   print("pass")
else:
   print("fail")
```

6. What does `elif` allow you to do?

`Answer:` it allows you to make a second conditional statement

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise

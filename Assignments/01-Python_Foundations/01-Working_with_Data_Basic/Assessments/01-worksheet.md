# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` append()

2. How can you remove an item from a list by value?  
   `Answer:` remove();

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` 2 , 4 , 6 , 8

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.
```
movies = ("Up", "World War Z", "Mario")
movie.append("Grown Ups")
movies.remove("Up)
print(movies)


---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` Tuples cant be modified after creation and lists can

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` no you cant because it is unmutable

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
nums = (5 , 3, 7)
x, y, z = nums
print(x)
print(y)
print(z)
```

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` Allows the user to obtain a value from the dictionary but also
            allows for a exeption check and response

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` for key, value in dict.items():

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
person = {'name' : 'jose', 'age' : '21', 'hobby' : 'games'}
print(person)
```

---

## 🧾 Submit Checklist

- [y] I practiced creating and modifying lists.
- [y] I understand how tuples are different from lists.
- [y] I accessed and looped through dictionary items.

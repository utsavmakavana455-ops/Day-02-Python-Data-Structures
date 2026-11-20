# Day 02 – Python Data Structures 🐍

Welcome to Day 2 of my 30 Days of Machine Learning journey!

Today, I learned three important Python data structures: Lists, Tuples, and Dictionaries.

## 🎯 Learning Objectives

- Understand Python Lists.
- Learn list indexing and slicing.
- Understand Python Tuples.
- Learn Python Dictionaries.
- Add, update, and remove elements.
- Practice with real-world examples.

---

## 1. Python Lists

A list stores multiple values in a single variable.

```python
languages = ["Python", "Java", "C++", "JavaScript"]

print(languages)
print(languages[0])
print(languages[-1])
```

### List Methods

```python
numbers = [10, 20, 30, 40]

numbers.append(50)
numbers.insert(1, 15)
numbers.remove(30)
numbers.pop()

print(numbers)
```

### List Slicing

```python
numbers = [10, 20, 30, 40, 50]

print(numbers[0:3])
print(numbers[1:4])
print(numbers[:3])
print(numbers[2:])
```

---

## 2. Python Tuples

A tuple stores multiple values but cannot be modified after creation.

```python
coordinates = (10, 20, 30)

print(coordinates)
print(coordinates[0])
print(coordinates[1])
```

### Tuple Properties

- Ordered
- Immutable
- Allows duplicate values
- Uses parentheses `()`

---

## 3. Python Dictionaries

A dictionary stores information as key-value pairs.

```python
student = {
    "name": "Alex",
    "age": 22,
    "country": "Germany",
    "grade": 90
}

print(student["name"])
print(student["age"])
print(student["grade"])
```

### Adding and Updating Values

```python
student["university"] = "TU Berlin"
student["age"] = 23

print(student)
```

### Dictionary Methods

```python
print(student.keys())
print(student.values())
print(student.items())
```

---

## 4. Practical Example – Student Database

```python
students = [
    {
        "name": "Alex",
        "age": 22,
        "marks": [80, 90, 85]
    },
    {
        "name": "John",
        "age": 23,
        "marks": [75, 85, 90]
    }
]

print(students[0]["name"])
print(students[0]["marks"])
print(students[1]["age"])
```

---

## 5. Coding Exercises

- [ ] Create a list of five programming languages.
- [ ] Add and remove elements from a list.
- [ ] Create a tuple with your personal information.
- [ ] Create a dictionary with your name, age, and country.
- [ ] Calculate the average of three student marks.

---

## 6. Key Differences

| Feature | List | Tuple | Dictionary |
|---|---|---|---|
| Syntax | `[]` | `()` | `{}` |
| Mutable | Yes | No | Yes |
| Ordered | Yes | Yes | Yes |
| Stores | Values | Values | Key-value pairs |

---

## 7. Why Is This Important for Machine Learning?

Python data structures are essential for:

- Organizing datasets.
- Storing features and labels.
- Managing student or customer records.
- Preparing data before training ML models.

These concepts will help me understand NumPy and Pandas in the upcoming lessons.

---

## 📚 Day 2 Summary

Today I learned:

- Python Lists
- List indexing and slicing
- List methods
- Python Tuples
- Python Dictionaries
- Key-value pairs
- Basic data organization

**Status:** Day 2 – In Progress

**Next:** Day 3 – Conditional Statements, For Loops and While Loops.

---

⭐ Consistency is the key to mastering Machine Learning. One day at a time! 🚀

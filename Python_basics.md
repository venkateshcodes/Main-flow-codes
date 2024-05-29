 Basics of Python and Its Data Structures

 Introduction
This file provides a basic introduction to Python and its core data structures, including lists, tuples, sets, and dictionaries, along with examples.

**Lists
Lists are ordered collections of items that are changeable and allow duplicate values.**

Creating a list
fruits = ["apple", "banana", "cherry"]
print(fruits)

Accessing elements
print(fruits[1])

Modifying elements
fruits[1] = "blueberry"
print(fruits)

Adding elements
fruits.append("date")
print(fruits)

Removing elements
fruits.remove("apple")
print(fruits)

Tuples
**Tuples are ordered collections of items that are unchangeable and allow duplicate values.**

Creating a tuple
vegetables = ("carrot", "broccoli", "lettuce")
print(vegetables)

Accessing elements
print(vegetables[2])

# Tuples are immutable, so you cannot modify elements

**Sets
Sets are unordered collections of unique items.**
Creating a set
numbers = {1, 2, 3, 4, 5}
print(numbers)

Adding elements
numbers.add(6)
print(numbers)
 Removing elements
numbers.remove(3)
print(numbers)

Sets do not allow duplicate values
numbers.add(4)
print(numbers)

**Dictionaries
Dictionaries are collections of key-value pairs that are unordered, changeable, and do not allow duplicates.**

Creating a dictionary
student = {"name": "John", "age": 20, "major": "Computer Science"}
print(student)

Accessing elements
print(student["name"])

Modifying elements
student["age"] = 21
print(student)

Adding elements
student["graduation_year"] = 2022
print(student)

Removing elements
del student["major"]
print(student)

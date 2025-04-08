
# 🎓 College Management System - Python CLI App

This is a **command-line-based college management system** built in Python that allows users to:

- Create a college
- Add students and teachers
- Display and search for students or teachers by roll number

This is a great beginner-to-intermediate level project to understand class inheritance, object-oriented programming (OOP), and managing lists of custom objects.

---

## 📌 Features

- 🔹 Add multiple colleges
- 🔹 Add students and teachers under each college
- 🔹 Display all students or teachers in a college
- 🔹 Search for a student or teacher across colleges using roll number

---

## 🧑‍💻 Technologies Used

- Python 3.x
- Object-Oriented Programming (OOP)

---

## 🧾 Class Structure

- `Person`: Base class with common attributes `rollno` and `name`.
- `Student`: Inherits from `Person` and adds `branch`.
- `Teacher`: Inherits from `Person` and adds `subject`.
- `College`: Contains lists of students and teachers, and handles operations.

---

## ⚠️ Common Fix (Important)

Make sure to fix the constructor method in each class:

```python
# Replace _init_ with __init__

def __init__(self, ...):
```

Python requires **double underscores** for constructors.

---

## 🚀 How to Run

1. Save the code as `college_system.py`.
2. Run in terminal or command prompt:
   ```bash
   python college_system.py
   ```
3. Follow the on-screen prompts to interact with the system.

---

## 📸 Sample CLI Interaction

```
Choose the Required option:
1. Create College.
2. Add Student.
3. Add Teacher.
...
Enter your Option: 1
Enter College Name: ABC College
College Added Successfully

<h1 align="center">🌟 Fundamental Booster 🌟</h1>
<h3 align="center">🐍 Interactive Personal Data Collector using Python 💻</h3>

<p align="center">
  <b>A beginner-friendly Python mini project to collect user details and display their data types, memory addresses, and approximate birth year ✨</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Project-Beginner%20Friendly-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-orange?style=for-the-badge" />
</p>

---

# 📖 Project Overview
**Fundamental Booster** is a simple and interactive Python project designed for **beginners** who want to practice the fundamentals of Python programming.

This program asks the user to enter:
- 👤 **Name**
- 🎂 **Age**
- 📏 **Height**
- 🔢 **Favourite Number**

After collecting the input, the program displays:
- the entered values
- their **data types**
- their **memory addresses**
- the user's **approximate birth year**

This project is useful for understanding how Python handles **variables, input, type conversion, and built-in functions**.

---

# ✨ Features
✔️ Interactive user input  
✔️ Uses multiple data types: `str`, `int`, `float`  
✔️ Displays **type of each variable** using `type()`  
✔️ Displays **memory address** using `id()`  
✔️ Calculates approximate **birth year** from age  
✔️ Great beginner project for learning Python basics  

---

# 🛠️ Tech Stack
| Technology | Purpose |
|-----------|---------|
| **Python 3** | Programming Language |
| **IDLE / VS Code / PyCharm** | To run the program |

---

# 📂 Project Structure
```bash
Fundamental-Booster/
│── Fundamental_Booster.py
│── README.md
│── screenshot.png
```

---

# 📸 Output Screenshot
<p align="center">
  <img src="image(25).png" alt="Fundamental Booster Output" width="900">
</p>

---

# 💻 Source Code
```python
print("Welcome to the Interactive Personal Data Collector!")
print()

name = str(input("Please enter your name: "))
age = int(input("Please enter your age: "))
height = float(input("Please enter your height in meters: "))
favourite_number = int(input("Please enter your favourite number: "))

print()
print("Thank you! Here is the information we collected:")
print()

print("Name:", name, "(Type:", type(name), "Memory Address:", id(name), ")")
print("Age:", age, "(Type:", type(age), "Memory Address:", id(age), ")")
print("Height:", height, "(Type:", type(height), "Memory Address:", id(height), ")")
print("Favorite_number:", favourite_number, "(Type:", type(favourite_number), "Memory Address:", id(favourite_number), ")")

print()
current_year = 2026
birth_year = current_year - age
print("Your birth year is approximately:", birth_year, "based on your age of:", age)

print()
print("Thank you for using the Personal Data Collector.Goodbye")
```

---

# ▶️ How to Run the Project
## Step 1: Save the Python file
Save your program with a file name like:

```bash
Fundamental_Booster.py
```

## Step 2: Open in Python IDE
You can run it in:
- **Python IDLE**
- **VS Code**
- **PyCharm**

## Step 3: Run the Program
Execute the file and enter the required details when asked.

## Step 4: View the Output
The program will display:
- your entered data
- variable type
- memory address
- approximate birth year 🎉

---

# 📚 Concepts Used
- `input()`
- `type casting`
- `str()`, `int()`, `float()`
- `type()`
- `id()`
- arithmetic operators
- variable handling
- output formatting

---

# 🎯 Learning Objectives
By making this project, you can practice:
- taking user input in Python
- converting one data type to another
- understanding **type of variables**
- understanding **memory address of variables**
- performing a simple calculation
- writing cleaner beginner-level Python code<img width="677" height="349" alt="Screenshot fundamental booster " src="https://github.com/user-attachments/assets/3765cce6-57b0-4d50-9a6d-1b8393b37d4c" />


---

# 📝 Sample Output
```bash
Welcome to the Interactive Personal Data Collector!

Please enter your name: Venya
Please enter your age: 21
Please enter your height in meters: 157.5
Please enter your favourite number: 2

Thank you! Here is the information we collected:

Name: Venya (Type: <class 'str'> Memory Address: 2043220934064)
Age: 21 (Type: <class 'int'> Memory Address: 140712592250408)
Height: 157.5 (Type: <class 'float'> Memory Address: 2043230078448)
Favorite_number: 2 (Type: <class 'int'> Memory Address: 140712592249800)

Your birth year is approximately: 2005 based on your age of: 21

Thank you for using the Personal Data Collector.Goodbye
```

---

# 🚀 Why this project is useful
This project is a great **foundation-building exercise** because it combines:
- user interaction
- variables
- type conversion
- Python built-in functions
- simple logic

It is perfect for students who are just starting with Python and want to create a small but meaningful project.

---

# 💖 Author Note
Made with dedication for **Python practice, logic building, and concept clarity** 🌸✨

---

<p align="center">
  ⭐ If you like this project, don't forget to give it a star on GitHub ⭐
</p>
<img width="677" height="349" alt="Screenshot fundamental booster " src="https://github.com/user-attachments/assets/b97bdec2-e177-4307-ba5b-78820e666b44" />

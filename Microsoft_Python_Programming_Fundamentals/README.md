# 🐍 Microsoft Python Programming Fundamentals (Coursera)

## 📘 Overview
This repository documents my full completion of the **Microsoft Python Programming Fundamentals** course on **Coursera**.  
It covers the entire pathway from Python basics through data structures, debugging, unit testing, and version control with Git & GitHub.

---

## 🧠 Skills Mastered
- ✅ Python syntax, variables, data types, and control flow  
- ✅ Lists, dictionaries, sets, tuples, sorting, and searching  
- ✅ Functions, classes, and modules (built-in & custom)  
- ✅ Debugging, exception handling, and best practices  
- ✅ Automated testing with **pytest**  
- ✅ Version control with **Git & GitHub**  
- ✅ Professional software portfolio creation  

---

## 🗂️ Course Modules Overview

### **1️⃣ Orientation & Setup**
- Python installation, environment setup  
- IDE options (VS Code, Jupyter, PyCharm)  
- Navigating Jupyter notebooks  

### **2️⃣ Python Fundamentals**
- Variables, syntax, input/output  
- Expressions, operations, and structure of Python programs  

### **3️⃣ Control Flow**
- `if`, `elif`, `else` statements  
- `for` and `while` loops  
- Code tracing and avoiding logical pitfalls  

### **4️⃣ Lists & Data Containers**
- Creating, slicing, and modifying lists  
- Practical list operations and exercises  

### **5️⃣ Functions, Classes, & Modules**
- Writing reusable functions  
- Understanding scope and modularity  
- Building and importing custom modules  
- Managing external libraries with `pip`  

### **6️⃣ Core Data Structures**
- Lists, tuples, dictionaries, and sets  
- Mutability and data manipulation  
- Sorting/searching algorithms and decision frameworks  

### **7️⃣ Error Handling & Debugging**
- Exceptions and try/except blocks  
- Using debuggers, breakpoints, and print statements  
- Developing a “debugging mindset”  

### **8️⃣ Testing with pytest**
- Unit testing fundamentals  
- pytest setup and execution  
- Fixtures, parametrization, and organized test suites  

### **9️⃣ Version Control with Git & GitHub**
- Git basics: init, add, commit, branch, merge  
- Setting up GitHub repositories  
- Pull requests, merges, and collaboration  
- Building a professional coding portfolio  

### **🔟 Final Project & Portfolio**
- Problem-solving with Python  
- Applying Git workflows in real-world projects  
- Creating a structured, testable codebase  

---

## 🧩 Example Snippets

### ✅ pytest Example
```python
def contains_five(xs):
    """Return True if the list contains the number 5."""
    return 5 in xs

def test_contains_five():
    my_list = [1, 3, 5, 7, 9]
    assert contains_five(my_list) is True
```
```
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/repo.git
git push -u origin main
```

```
Microsoft_Python_Programming_Fundamentals/
│
├── Learnings/
│   ├── 01_Orientation_Tooling/
│   ├── 02_Python_Fundamentals/
│   ├── 03_Control_Flow/
│   ├── 04_Lists/
│   ├── 05_Functions_Classes_Modules/
│   ├── 06_Data_Structures/
│   ├── 07_Debugging_Exceptions/
│   ├── 08_Testing_pytest/
│   ├── 09_Git_GitHub/
│   └── 10_Portfolio_Capstone/
│
├── code_samples/
│   ├── contains_five.py
│   └── tests/test_contains_five.py
│
├── cheatsheets/
│   ├── python_basics.md
│   ├── pytest_quickstart.md
│   └── git_github_quickstart.md
│
└── README.md
```

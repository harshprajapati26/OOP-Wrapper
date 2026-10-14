## 📌 OOP Wrapper – Employee Management System

A console-based **Employee Management System** built with Python to demonstrate Object-Oriented Programming (OOP) concepts such as classes, inheritance, encapsulation, method overloading, method overriding, and user interaction through a menu-driven interface.

## 📌 Project Overview

This project models people and employees using a base `Employee` class and specialized `Manager` and `Developer` classes. Users can create records and display details through a simple console menu.

## 🎯 Objectives

- Demonstrate core Python OOP concepts in a practical project.
- Represent people, employees, managers, and developers using classes.
- Keep sensitive employee information encapsulated with getters and setters.
- Use inheritance and method overriding to customize employee types.
- Provide a menu-driven interface for creating objects and viewing details.

## ✨ Features

- **Person creation** — store a person's name and age.
- **Employee creation** — store employee ID and salary along with personal details.
- **Manager creation** — add a department (for example, HR, Finance, or Sales).
- **Developer creation** — add a programming language (for example, Python or Java).
- **Encapsulation** — keep fields such as employee ID and salary private and access them through methods.
- **Inheritance** — derive `Manager` and `Developer` from `Employee`.
- **Method overriding** — customize `display()` for specialized employee details.
- **Constructor overloading pattern** — support multiple ways to create employee objects using optional parameters or equivalent Python techniques.
- **Resource cleanup** — use a destructor where appropriate.
- **Menu-driven console UI** — create records, display details, and exit.

## 🧠 OOP Concepts Demonstrated

| Concept | How it is used |
|---|---|
| Class and object | Model people and employee records |
| Inheritance | `Manager` and `Developer` inherit from `Employee` |
| Encapsulation | Private employee ID and salary fields with getters/setters |
| Method overriding | Subclasses override `display()` |
| Constructor overloading | Python-friendly alternatives such as default/optional arguments |
| `self` | Refers to the current instance and its attributes |
| `super()` | Calls parent-class methods or constructors |
| `issubclass()` | Checks whether a class inherits from `Employee` |
| Destructor | Demonstrates cleanup with `__del__()` |
| User interface | A numbered console menu handles user choices |

> **Note:** Python does not support traditional method or constructor overloading in the same way as languages such as Java. It is commonly demonstrated with default arguments, optional parameters, or other Python patterns.

## 🛠️ Requirements

- Python 3.8 or later (Python 3.x should work if the code uses compatible syntax)
- A terminal or command prompt

No external packages are required for a standard console implementation.

## 🚀 Getting Started

### 1. Clone the repository

### 2. Open the project folder

### 3. Run the program

## 💻 Example Console Menu

```text
--- Python OOP Project: Employee Management System ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Show Details
5. Exit
```

### Example workflow

1. Choose **Create a Person** and enter a name and age.
2. Choose **Create an Employee** and enter the name, age, employee ID, and salary.
3. Choose **Create a Manager** and enter the employee details and department.
4. Choose **Show Details** and select the type of details to display.
5. Choose **Exit** to close the program.

## 📂 Suggested Project Structure

```text
OOP-Wrapper/
├── main.py          # Main program and menu
├── README.md        # Project documentation


Adjust the filenames above to match your repository.

## 🔮 Possible Improvements

- Add a `Developer` creation option to the menu if it is not already included.
- Validate age, salary, and employee ID input.
- Store multiple employees in a list or dictionary.
- Add search, update, and delete functionality.
- Save employee records to a JSON file or database.
- Add automated tests for classes and methods.

## 🎥 Project Demonstration Video

### ▶️ Video Link

https://drive.google.com/file/d/15c_JYeGu3O-4qtvPTdiQmuYXOCbQjvnS/view?usp=drive_link

## 🤝 Contributing

Contributions and suggestions are welcome. Fork the repository, create a branch, make your changes, and open a pull request.

## 📄 License

**ONLY FOR EDUCATION PERPOSE**
**Created as a Python OOP learning project. BY HARSH PRAJAPATI**

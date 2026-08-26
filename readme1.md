# 🐍 Python OOPs — Basic to Advanced

A structured **Python Object-Oriented Programming (OOP)** practice series designed to build strong OOP concepts from **basic to advanced level** through theory, coding examples, and hands-on practice.

The goal of this series is to understand how OOP works in Python and become comfortable designing real-world programs using classes and objects.

---

## 🎯 Series Goal

This series focuses on learning Python OOP step-by-step:

**Basics → Core Concepts → Intermediate → Advanced → Real-World Practice**

By the end of the series, you should be able to:

* Create and use classes and objects
* Understand constructors and instance attributes
* Work with instance, class, and static methods
* Implement encapsulation
* Understand inheritance and polymorphism
* Use abstraction effectively
* Work with special/magic methods
* Design reusable and maintainable classes
* Apply OOP concepts in real-world projects

---

## 📚 Topics Covered

### 🟢 Day 1 — OOP Fundamentals

* What is OOP?
* Class
* Object
* `__init__()`
* `self`
* Instance Attributes
* Instance Methods
* Class Attributes
* Class Methods
* Static Methods

### 🟡 Day 2 — Encapsulation

* Public Attributes
* Protected Attributes
* Private Attributes
* Name Mangling
* Getters & Setters
* `@property`
* `@setter`
* Data Validation

### 🟠 Day 3 — Inheritance

* What is Inheritance?
* Parent & Child Classes
* Single Inheritance
* Multilevel Inheritance
* Multiple Inheritance
* Hierarchical Inheritance
* `super()`

### 🔵 Day 4 — Polymorphism

* Method Overriding
* Method Overloading concepts
* Duck Typing
* Polymorphism with Inheritance

### 🟣 Day 5 — Abstraction

* What is Abstraction?
* Abstract Classes
* Abstract Methods
* `ABC`
* `@abstractmethod`

### 🔴 Day 6 — Magic / Dunder Methods

* `__str__()`
* `__repr__()`
* `__len__()`
* `__eq__()`
* `__lt__()`
* `__add__()`
* Other useful dunder methods

### 🟤 Day 7 — Advanced OOP

* Composition
* Aggregation
* Association
* Dependency
* Method Resolution Order (MRO)
* Multiple Inheritance
* `isinstance()`
* `issubclass()`

### ⚫ Day 8 — OOP Design Concepts

* SOLID Principles
* DRY Principle
* Coupling
* Cohesion
* Reusability
* Maintainability

### 🟩 Day 9 — Real-World OOP Practice

Building practical systems using OOP concepts:

* Bank Account System
* Employee Management System
* Library Management System
* Shopping Cart
* ATM System
* Student Management System

### 🚀 Day 10 — OOP Project

A complete mini-project combining the concepts learned throughout the series.

---

## 🗂️ Repository Structure

```text
Python-OOP-Series/
│
├── Day-01/
│   ├── oop_basics.ipynb
│   └── README.md
│
├── Day-02/
│   ├── encapsulation.ipynb
│   └── README.md
│
├── Day-03/
│   ├── inheritance.ipynb
│   └── README.md
│
├── Day-04/
│   ├── polymorphism.ipynb
│   └── README.md
│
├── Day-05/
│   ├── abstraction.ipynb
│   └── README.md
│
├── Day-06/
│   ├── magic_methods.ipynb
│   └── README.md
│
├── Day-07/
│   ├── advanced_oop.ipynb
│   └── README.md
│
├── Day-08/
│   ├── oop_design.ipynb
│   └── README.md
│
├── Day-09/
│   ├── real_world_practice.ipynb
│   └── README.md
│
└── Day-10/
    ├── oop_project.ipynb
    └── README.md
```

---

## 🛠️ Technologies Used

* **Python 🐍**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 📈 Learning Approach

Each day follows a simple learning workflow:

```text
📖 Concept
   ↓
🧠 Understanding
   ↓
💻 Coding Example
   ↓
✍️ Practice
   ↓
🔥 Real-World Problem
```

The focus is not just on memorizing OOP definitions, but on **writing and understanding the code**.

---

## 💡 Example

A simple Python class:

```python
class BankAccount:

    def __init__(self, balance, owner):
        self.balance = balance
        self.owner = owner

    def deposit(self, amount):
        self.balance += amount

    def withdraw(self, amount):
        if amount <= self.balance:
            self.balance -= amount
        else:
            print("Insufficient balance")
```

Creating an object:

```python
account = BankAccount(5000, "Manish")

account.deposit(2000)

print(account.balance)
```

Output:

```text
7000
```

---

## 🎓 Who Is This For?

This series is useful for:

* Python beginners
* Data Science learners
* Machine Learning learners
* Software Development students
* Anyone preparing for Python interviews
* Anyone who wants to understand OOP practically

---

## 🚧 Progress

| Day    | Topic               | Status         |
| ------ | ------------------- | -------------- |
| Day 1  | OOP Fundamentals    | ✅ Completed    |
| Day 2  | Encapsulation       | 🔄 In Progress |
| Day 3  | Inheritance         | ⏳ Upcoming     |
| Day 4  | Polymorphism        | ⏳ Upcoming     |
| Day 5  | Abstraction         | ⏳ Upcoming     |
| Day 6  | Magic Methods       | ⏳ Upcoming     |
| Day 7  | Advanced OOP        | ⏳ Upcoming     |
| Day 8  | OOP Design          | ⏳ Upcoming     |
| Day 9  | Real-World Practice | ⏳ Upcoming     |
| Day 10 | Final Project       | ⏳ Upcoming     |

---

## 🚀 Why This Series?

OOP is one of the most important concepts in Python, especially when working with:

* Data Science
* Machine Learning
* Web Development
* Automation
* APIs
* Large-scale applications
* Production-level Python projects

This series is my journey of strengthening Python OOP concepts through **consistent coding and practical implementation**.

---


If you find this series useful, consider giving the repository a ⭐ on GitHub.

Happy Coding! 🐍🔥

**Keep Learning • Keep Building • Keep Pushing**

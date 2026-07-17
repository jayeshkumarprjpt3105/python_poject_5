# Employee Management System

A simple **Employee Management System** built using **Python Object-Oriented Programming (OOP)** concepts.

## Features

- Create Employee
- Create Manager
- Create Developer
- Display All Records
- Menu Driven Program
- Uses Inheritance
- Uses Encapsulation (Private Variables)
- Uses Method Overriding
- Uses `super()` Constructor

---

## OOP Concepts Used

### 1. Class
- Employee
- Manager
- Developer

### 2. Inheritance
- Manager inherits from Employee
- Developer inherits from Employee

### 3. Encapsulation
Private variables:

```python
self.__emp_id
self.__salary
```

Getter and Setter methods:

```python
get_salary()
set_salary()
```

### 4. Method Overriding

```python
display()
```

is overridden in:

- Manager
- Developer

### 5. super()

```python
super().__init__(...)
```

is used to call the parent constructor.

---

## Project Structure

```
Employee
│
├── Manager
└── Developer
```

---

## Menu

```
1. Create Employee
2. Create Manager
3. Create Developer
4. Show All
5. Exit
```

---

## Example Output

```
1. Create Employee
2. Create Manager
3. Create Developer
4. Show All
5. Exit

Enter your choice: 1

Enter Name: Jayesh
Enter Age: 21
Enter Employee ID: EMP101
Enter Salary: 50000

Employee Created:
Name: Jayesh, Age: 21, ID: EMP101, Salary: ₹50000
```

---

## Requirements

- Python 3.x

No external libraries are required.

---

## How to Run

```bash
python employee_management.py
```

---

## Author

**Jayesh Kumar**

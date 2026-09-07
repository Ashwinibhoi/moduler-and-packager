# Multi-Utility Toolkit 🛠️

A Python-based **Multi-Utility Toolkit** that provides multiple useful utilities through a simple menu-driven interface.

## 📌 Features

The toolkit includes the following operations:

1. **Datetime and Time Operations**

   * Display current date and time
   * Calculate difference between two dates
   * Format dates
   * Stopwatch
   * Countdown Timer

2. **Mathematical Operations**

   * Calculate factorial
   * Calculate compound interest
   * Trigonometric calculations
   * Calculate area of geometric shapes

3. **Random Data Generation**

   * Generate random numbers
   * Generate random lists
   * Generate random passwords
   * Generate random OTPs

4. **Generate Unique Identifiers**

   * Generate UUIDs using Python's `uuid` module

5. **File Operations**

   * Create a new file
   * Write data to a file
   * Read file contents
   * Append data to a file

6. **Explore Module Attributes**

   * Explore the attributes and functions available inside Python modules using `dir()`

---

## 🖥️ Main Menu

```text
=======================================
Welcome to Multi-Utility Toolkit
=======================================
Choose an option:
1. Datetime and Time Operations
2. Mathematical Operations
3. Random Data Generation
4. Generate Unique Identifiers (UUID)
5. File Operations
6. Explore Module Attributes (dir())
7. Exit
=======================================
```

---

## 📅 Datetime and Time Operations

This section provides different date and time utilities.

### Example

```text
Enter your choice: 1

================================
Datetime and Time Operations:
================================
1. Display current date and time
2. Calculate difference between two dates/times
3. Format date into custom format
4. Stopwatch
5. Countdown Timer
6. Back to Main Menu
================================

Enter your choice: 1

Current Date and Time: 2026-09-03 09:00:28
```

### Date Difference Example

```text
Enter your choice: 2
Enter the first date (YYYY-MM-DD): 2024-12-25
Enter the second date (YYYY-MM-DD): 2025-01-04

Difference: 10 days
```

---

## 🧮 Mathematical Operations

The Mathematical Operations section performs common mathematical calculations.

### Factorial

```text
Enter your choice: 1
Enter a number: 5

Factorial: 120
```

### Compound Interest

```text
Enter your choice: 2
Enter principal amount: 100
Enter rate of interest (in %): 5
Enter time (in years): 2

Compound Interest: 10.25
```

The compound interest formula used is:

```text
CI = P × (1 + R/100)^T - P
```

Where:

* `P` = Principal amount
* `R` = Rate of interest
* `T` = Time in years

---

## 🎲 Random Data Generation

This section generates different types of random data.

### Random Password Example

```text
Enter your choice: 3
Enter password length: 8

Generated Password: 03$2#O)W
```

The generated password can contain a combination of letters, numbers, and special characters.

---

## 🆔 Generate Unique Identifiers

The UUID section generates a unique identifier using Python's `uuid` module.

### Example

```text
================================
Generate Unique Identifiers (UUID)
================================
Generated UUID: be054896-2b84-46bd-9d5b-b6551b0af602
```

---

## 📁 File Operations

The File Operations section allows basic file handling.

### Available Operations

```text
1. Create a new file
2. Write to a file
3. Read from a file
4. Append to a file
5. Back to Main Menu
```

### Create File

```text
Enter your choice: 1
Enter file name: example.txt

File created successfully!
```

### Write Data

```text
Enter your choice: 2
Enter file name: example.txt
Enter data to write: This is a sample file

Data written successfully!
```

### Read File

```text
Enter your choice: 3
Enter file name: example.txt

File content:
This is a sample file
```

---

## 🔍 Explore Module Attributes

The toolkit also demonstrates Python's built-in `dir()` function.

### Example

```text
Enter built-in module name (e.g., math, os, time): math
```

The program displays the available attributes and functions of the selected module.

Example:

```text
Attributes in 'math':
['__doc__', '__loader__', '__name__', '__package__',
'acos', 'asin', 'atan', 'ceil', 'cos', 'degrees',
'exp', 'factorial', 'floor', 'log', 'pi', 'pow',
'radians', 'sin', 'sqrt', 'tan', ...]
```

---

## 🛠️ Technologies Used

* **Python 3**
* `datetime`
* `time`
* `math`
* `random`
* `uuid`
* `os`

---

## 📂 Project Structure

```text
Multi-Utility-Toolkit/
│
├── main.py
├── example.txt
└── README.md
```

> File names can be changed according to your actual project structure.

---

## ▶️ How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

### 2. Clone or Download the Project

Download the project files to your computer.

### 3. Run the Program

Open a terminal in the project folder and run:

```bash
python main.py
```

### 4. Select an Option

Choose an option from the displayed menu and follow the instructions.

---

## 🎯 Learning Objectives

This project demonstrates practical use of:

* Python functions
* Conditional statements
* Loops
* User input
* Exception handling
* Date and time operations
* Mathematical operations
* Random data generation
* UUID generation
* File handling
* Python modules
* `dir()` function
* Menu-driven programming

---

## 📸 Sample Output

The program successfully demonstrates:

* Current date and time
* Date difference calculation
* Factorial calculation
* Compound interest calculation
* Random password generation
* UUID generation
* File creation, writing, and reading
* Module attribute exploration

---

## 👩‍💻 Author

**Ashwini Bhoi**

---

## 📜 License

This project is created for **learning and educational purposes**.

# Python Mini Project

This repository contains small Python projects focused on clean coding, statistics, and data analysis using real datasets.

---

## 🚀 Features

### 1. Function Mapping (No if-else)

Instead of long if-else statements, operations are handled using a dictionary:

```python
def do_something(operation, x, y):  
    operations = {
        "mul": lambda a, b: a * b,
        "add": lambda a, b: a + b,
        "sub": lambda a, b: a - b,
    }
    return operations[operation](x, y)
```

---

### 2. Average Function using *args

```python
def avg(*args):
    return sum(args) / len(args)
```

---

### 3. Iris Dataset Analysis

- Loaded dataset using pandas
- Visualized data using seaborn
- Implemented:
  - Covariance function
  - Covariance matrix
  - Correlation matrix
- Verified results using NumPy

---

### 4. Laptop Price Analysis

Dataset: `laptop_price.csv`

#### Includes:
- Price distribution
- Average price per company
- Operating system cleaning
- RAM vs price analysis
- Storage type extraction

---

### 5. Extra Analysis

- Most common RAM sizes
- CPU type vs price

---

## 🛠️ Tech Stack

- Python
- pandas
- numpy
- matplotlib
- seaborn

---

## ▶️ Installation

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 📁 Files

- iris.csv
- laptop_price.csv
- Python scripts / notebook

---

## 📌 Notes

- Demonstrates replacing if-else with dictionaries
- Shows use of *args for flexible functions
- Includes basic data cleaning and visualization

---

## ✨ Author

Belyanesh Mossie

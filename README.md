# Python Basics for DevOps

## Overview

Python is a **dynamically typed language**, which means you do not need to explicitly specify the data type of a variable while declaring it. This is different from **statically typed languages** like **Golang**, where variable types must be defined upfront.

Python is widely used in **DevOps** due to its simplicity, readability, and extensive ecosystem.

---

## Why Python for DevOps?

Python is commonly used in DevOps for:

* Interacting with **external APIs** (AWS, Azure, GCP, GitHub, Jira, etc.)
* Writing **automation scripts**
* **Cross-platform** scripting (Linux, Windows, macOS)
* Infrastructure automation and configuration management
* CI/CD pipeline integrations

---

## Python Syntax

Python syntax is **strict and indentation-based**.

* Spaces and indentation are **mandatory** and define code blocks
* Incorrect indentation will result in syntax errors

Modern code editors like **VS Code** help by:

* Highlighting syntax errors
* Enforcing indentation rules
* Providing auto-completion and linting

---

## Python Data Types

### 1. String

Used to represent text data.

```python
name = "DevOps"
```

Common built-in functions:

* `lower()`
* `upper()`
* `split()`
* `replace()`
* `len()`

---

### 2. Integer and Float

Used to represent numeric data.

```python
count = 10        # int
percentage = 99.5 # float
```

Common built-in functions:

* `type()`
* `int()`
* `float()`
* `round()`

---

### 3. List and Tuple

Used to store multiple values.

**List (Mutable)**

```python
servers = ["web", "app", "db"]
```

Common functions:

* `append()`
* `remove()`
* `sort()`
* `len()`

**Tuple (Immutable)**

```python
ports = (80, 443, 22)
```

Common functions:

* `count()`
* `index()`

---

### 4. Dictionary

Used to store key-value pairs.

```python
config = {
    "env": "prod",
    "region": "ap-south-1"
}
```

Common functions:

* `keys()`
* `values()`
* `items()`
* `get()`

---

## Built-in Functions

Each Python data type provides **built-in functions** to handle common use cases efficiently. These are maintained as part of Python’s standard library and official documentation.

Refer to the official Python documentation for more details:

* [https://docs.python.org/3/](https://docs.python.org/3/)

---

## Repository Purpose

This repository is intended to:

* Cover **Python fundamentals** from a DevOps perspective
* Demonstrate real-world scripting use cases
* Serve as a reference for automation and infrastructure tasks

---

## Tools Recommended

* **VS Code** (Python extension)
* **Python 3.x**
* **Virtual Environments (venv)**

---

Happy Automating 🚀

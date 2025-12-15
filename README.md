# GSE301-PYTHON-PROJECT: Student Academic Performance Analysis System

## 📝 Project Description

This repository contains the solution for the **GSE301 Data Science: Python Fundamentals** project. The core objective was to develop a console-based application in Python that stores, processes, and analyzes mock student academic data for a specific department.

The project integrates fundamental Python concepts, including data structures, control flow, functions, and error handling, organizing them into a practical and interactive academic performance analysis workflow.

## ✨ Key Features Implemented

The system successfully demonstrates the following core requirements of the Python Fundamentals course:

* **Diverse Data Storage:** Utilizes a combination of Python's built-in data structures:
    * **Dictionaries** (for detailed student profiles and grades).
    * **Lists** (for grouping student profiles and course names).
    * **Sets** (for unique course tracking).
    * **Tuples** (for fixed department information).
* **Grading Logic:** Implements functions using **`IF ELIF ELSE`** to assign grades based on scores, complemented by **`MATCH CASE`** for contextual feedback.
* **Robust Input Handling:** Ensures data integrity through type conversion (string to `int`/`float`) and uses **`Try Except`** blocks to handle invalid user inputs (e.g., non-numeric data) and range validation.
* **Data Analysis Techniques:** Demonstrates essential Python operations:
    * **List Slicing** (to extract subsets of scores).
    * **Set Operations** (to find intersection, union, and difference between student groups).
* **Eligibility Checker:** Features a function that uses **logical operators (`and`, `or`)** to determine a student's eligibility for graduation based on their CGPA, outstanding courses, and active status.
* **Interactive Interface:** Provides a console menu system, driven by a `WHILE` loop and **`MATCH CASE`**, to allow users to interact with the student data.

# Student Data Management System

## Overview

This project implements a simple Student Data Management System using core Python data structures and techniques. The goal is to efficiently store, filter, and process student records while demonstrating the use of lists, tuples, sets, list comprehensions, and generator expressions.

---

## Features Implemented

### 1. Student Data Storage

- Student records are stored as **tuples** in a list.
- Each student includes:
  - ID
  - Name
  - Major

---

### 2. Filtering Students

- Implemented `filter_students_by_major` in `filter.py`.
- Uses a **list comprehension** to return students matching a specific major.

---

### 3. Data Formatting & Display

- Implemented `format_student_data` in `data_processing.py`:
  - Formats student data into a readable string.

- Implemented `display_students`:
  - Iterates through student records and prints formatted output.

---

### 4. Unique Majors Tracking

- Implemented `unique_majors` in `set_operations.py`.
- Uses a **set comprehension** to extract unique majors from student records.

---

### 5. Generator-Based Data Processing

- Implemented `student_generator` in `data_generator.py`.
- Uses a **generator expression** to lazily filter students by major.
- Improves memory efficiency when working with large datasets.

---

## Key Concepts Demonstrated

- Lists and Tuples for structured data storage
- List Comprehensions for efficient filtering
- Generator Expressions for memory-efficient processing
- Sets for tracking unique values
- Function design and parameter usage

---

## Summary

This project demonstrates how Python’s built-in data structures and comprehension techniques can be used to build a clean, efficient, and scalable system for managing and processing structured data.

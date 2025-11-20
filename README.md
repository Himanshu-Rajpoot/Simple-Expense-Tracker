# Expense Tracker Project

## Project Title

**Simple Expense Tracker**

---

## Features (Functional Requirements)

- Add new expenses with date, category, amount, and description.
- View all recorded expenses.
- View expenses by category.
- Display summary statistics (total spent, average expense).
- Save all data persistently in a CSV file.

---

## Non-Functional Requirements

- Usable Command-Line Interface (CLI).
- Reliable input validation.
- Data integrity with simple CSV file storage.
- Modular, readable Python code with comments.
- Error handling for file operations and inputs.

---

## Modules

- `main.py` — Core driver program and menu interface
- `expense_manager.py` — Functions to add, view, summarize expenses and handle file I/O
- `utils.py` — Helper functions for input validation and formatting

---

## File Storage

- `expenses.csv` — Stores expense records (Date, Category, Amount, Description)

---

## Diagrams and Documentation

- Flowchart or pseudocode of main functions.
- Simple CSV structure explanation.
- `README.md` with project overview, usage instructions, and structure.
- Project report detailing objectives, functionality, design decisions, and testing.

---

## Overview

This project is a Python-based expense management application designed to help users track and manage their expenses efficiently. It includes functionality for expense entry, categorization, and reporting.

---

## Setup Instructions

Follow these steps to set up the project environment and run the application:

1. **Clone the repository:**

2. **Create and activate a Python virtual environment:**

3. **Install dependencies:**
*(Leave requirements.txt empty if you only use built-in modules.)*

4. **Run the application:**

---

## Code Details

### main.py

- Acts as the entry point of the application.
- Manages the main program flow, including user interaction.
- Imports and uses functions from `expense_manager.py` to handle expense operations.

### expense_manager.py

- Contains core functions and classes for managing expenses.
- Functions include adding new expenses, listing expenses, and deleting entries.
- Handles data storage and retrieval (using CSV or in-memory structures).

---



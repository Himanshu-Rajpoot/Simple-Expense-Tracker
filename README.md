#Expense Tracker Project

##Project Title

-->Simple Expense Tracker

**Features (Functional Requirements)

*Add new expenses with date, category, amount, and description.
*View all recorded expenses.
*View expenses by category.
*Display summary statistics (total spent, average expense).
*Save all data persistently in a CSV file.

**Non-Functional Requirements

*Usable Command-Line Interface (CLI).
*Reliable input validation.
*Data integrity with simple CSV file storage.
*Modular, readable Python code with comments.
*Error handling for file operations and inputs.

#Modules

*main.py — core driver program, menu interface
*expense_manager.py — functions to add, view, summarize expenses and file I/O
*utils.py — helper functions for input validation and formatting

#File Storage

*expenses.csv — stores expense records (Date, Category, Amount, Description)
*Diagrams and Documentation
*Flowchart or pseudocode of main functions.
*Simple CSV structure explanation.
*README.md with project overview, usage instructions, and structure.
*Project report detailing objectives, functionality, design decisions, and testing.


#Overview

This project is a Python-based expense management application designed to help userstrack and manage their expenses efficiently. It includes functionality for expense entry, categorization, and reporting.

#Setup Instructions

Follow these steps to set up the project environment and run the application:

1. *Clone the repository:

git clone https://github.com/username/expense-manager.git
cd expense-manager

2. *Create and activate a Python virtual environment:

python3 -m venv venv
source venv/bin/activate  


3. *Install dependencies:

pip install -r requirements.txt

4. *Run the application:

python main.py


# CODE DETAILS

**main.py

*Acts as the entry point of the application.
*Manages the main program flow, including user interaction.
*Imports and uses functions from expense_manager.py to handle expense operations.

**expense_manager.py

*Contains core functions and classes for managing expenses.
*Functions include adding new expenses, listing expenses, and deleting entries.
*Handles data storage and retrieval (potentially from CSV or in-memory).

# Example Usage

**From command line

python main.py
from expense_manager import add_expense

add_expense(date="2025-11-20", category="Food", amount=15.50, description="Lunch")
Project Structure

text
expense-manager/
│
├── main.py             # Entry point script handling user interface/flow
├── expense_manager.py  # Core expense management functions and data handling
├── requirements.txt    # List of dependencies
├── README.md           # Project documentation
└── data/               # (Optional) Folder to store any data files (e.g., expense records)

# Library OOP Practical Assignment 1

An educational Jupyter Notebook that demonstrates object-oriented programming concepts and Python data structures through a small, in-memory library-management example. The notebook defines books and physical book copies, registers students, records loans and returns, and calculates late-return fines.

## Features

- Demonstrates **encapsulation**, **inheritance**, **abstraction**, and **polymorphism**.
- Defines abstract `LibraryItem` and `Person` base classes, with `Book`, `ReferenceBook`, and `Student` implementations.
- Tracks a book catalogue by ISBN, physical copies by unique copy ID, and student loans.
- Validates required names and contact details, ISBN formats, IDs, object types, availability, and date ordering.
- Prevents reference books from being borrowed.
- Calculates a fine of **UGX 1,000 per late day** after a book is returned.
- Demonstrates lists, tuples, dictionaries, and sets in practical roles.
- Includes runnable examples of successful borrowing and returning, as well as validation errors.

## Technologies

- Python
- Jupyter Notebook (`.ipynb`)
- Python standard library: `abc` and `datetime`

The notebook metadata records Python **3.13.12**. No third-party Python packages are imported by the project code.

## Requirements and installation

You need Python and a Jupyter Notebook environment. The project contains no dependency or environment manifest; Jupyter is the interface used to open and run the notebook, not an imported project library.

To install the classic Jupyter Notebook interface if it is not already available:

```bash
python -m pip install notebook
```

## Usage

From the project root, start Jupyter Notebook:

```bash
jupyter notebook
```

Open `OOP_Practical_Assignment_1_Library_Enhanced.ipynb`, then run its cells **from top to bottom**. The notebook first defines the library classes and helper functions, then creates sample books, copies, and a student before demonstrating borrowing, returning, fine calculation, data structures, and validation errors.

The examples use dates in September 2026. State is held in Python objects and in-memory collections for the current notebook kernel session; restarting the kernel clears it.

## Project structure

```text
.
├── README.md
└── OOP_Practical_Assignment_1_Library_Enhanced.ipynb
```

All application logic and demonstrations are in the notebook. There is no separate command-line application, database, or test suite in the project files.

## Contributor

The notebook credits **Ajak Deng Garang Deng** (Reg. No. **M25B38/031**), **BSDS**, Year **2:1**.

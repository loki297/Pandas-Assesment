# Pandas Data Analysis & Data Cleaning

A practical Jupyter Notebook covering **Pandas, NumPy, data analysis, code correction, edge cases, and data cleaning**.

## Overview

This notebook provides hands-on practice with Pandas and NumPy through four sections:

- **Section A – Output Prediction**
- **Section B – Code Correction**
- **Section C – Edge Cases**
- **Section D – Scenario-Based Data Cleaning**

The exercises progress from basic Pandas operations to practical data-cleaning problems.

## Topics Covered

- NumPy arrays and vectorization
- Pandas Series and DataFrames
- Boolean filtering
- Descriptive statistics
- Group-wise analysis
- Correlation analysis
- CSV file handling
- Sorting and data selection
- Missing-value handling
- NumPy broadcasting
- Outlier analysis
- Duplicate removal
- Data standardization
- Numeric conversion
- Invalid-value detection
- Data validation

## Notebook Structure

### Section A – Output Prediction

Covers:

1. Array operations and vectorization
2. Boolean filtering
3. Descriptive statistics
4. Group-wise analysis
5. Positive correlation
6. Negative correlation

### Section B – Code Correction

Covers:

1. CSV and header handling
2. Salary sorting and selection
3. Missing-value replacement
4. Correlation calculation

### Section C – Edge Cases

Covers:

1. NumPy broadcasting
2. CSV parsing and data types
3. Outliers and statistical measures

### Section D – Scenario-Based Data Cleaning

Uses a student assessment dataset containing common data-quality issues such as:

- Inconsistent department names
- Missing marks
- Duplicate records
- Text-based marks
- `Absent` and `NA` values
- Invalid marks outside the `0–100` range

The data-cleaning workflow includes:

```text
Load Data
    ↓
Inspect Data
    ↓
Standardize Values
    ↓
Remove Duplicates
    ↓
Convert Data Types
    ↓
Handle Missing Values
    ↓
Identify Invalid Values
    ↓
Validate Data
```

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Project Structure

```text
.
├── Lokesh_Pandas.ipynb
├── student_assessment_dirty.csv
└── README.md
```

### Files

**`Lokesh_Pandas.ipynb`**  
Main Jupyter Notebook containing the questions, code, outputs, and explanations.

**`student_assessment_dirty.csv`**  
Dataset used for the scenario-based data-cleaning exercises.

**`README.md`**  
Documentation for the project and instructions for running the notebook.

## Getting Started

### 1. Install Dependencies

```bash
pip install pandas numpy jupyter
```

### 2. Start Jupyter Notebook

```bash
jupyter notebook
```

### 3. Open the Notebook

Open:

```text
Lokesh_Pandas.ipynb
```

For **Section D**, make sure `student_assessment_dirty.csv` is placed in the same directory as the notebook.

## Learning Outcomes

After completing this notebook, you will be able to:

- Work with Pandas DataFrames and NumPy arrays.
- Perform basic data analysis and statistical operations.
- Identify and correct common Pandas coding issues.
- Handle missing and inconsistent data.
- Remove duplicate records.
- Convert text values into suitable numeric formats.
- Identify invalid data and outliers.
- Apply a structured data-cleaning workflow.
- Validate data after preprocessing.

## Author

**CH Lokesh Kumar**

---

> **Pandas | Data Analysis | Data Cleaning**

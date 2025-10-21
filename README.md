# Data Analysis with NumPy - A Comprehensive Guide

## Description

This repository contains a Jupyter Notebook (`Data_Analysis_With_Numpy_ipynb.ipynb`) providing a detailed introduction and guide to Data Analysis using the NumPy library in Python. The notebook covers fundamental concepts, core functionalities, and practical examples essential for scientific computing, data science, and machine learning tasks.

Explanations and code comments are provided in both **English** and **Bengali** 🇧🇩.

## Topics Covered

The notebook systematically explores various aspects of NumPy, including:

* **Introduction to NumPy:**
    * Why NumPy is faster than Python lists (Homogeneous types, Contiguous memory).
    * Vectorization and SIMD.
    * Common use cases (Linear Algebra, Statistics, Foundation for other libraries).
* **The `ndarray` Object:**
    * Creating 1D, 2D, and 3D arrays.
    * Core attributes (`ndim`, `shape`, `size`, `dtype`).
    * Data type handling (Upcasting, Type control, `astype`).
* **Array Creation Methods:**
    * From existing Python structures (lists, tuples, sets, dictionaries).
    * From scratch (`zeros`, `ones`, `empty`, `full`, `zeros_like`, etc.).
    * Using ranges (`arange`, `linspace`, `logspace`).
    * Generating random data (`rand`, `randint`, `uniform`).
    * Creating special matrices (`diag`, `eye`).
* **Array Manipulation:**
    * Reshaping (`reshape`).
    * Flattening (`flatten`, `ravel`).
    * Combining arrays (`concatenate`).
    * Transposing (`.T`).
    * Splitting arrays (`split`, `array_split`).
* **Indexing and Slicing:**
    * Basic indexing and slicing for 1D and 2D arrays.
    * Views vs. Copies.
    * Advanced Indexing (Integer array indexing, Boolean indexing/filtering).
    * Iterating over arrays (`nditer`).
* **Mathematical and Statistical Operations:**
    * Element-wise arithmetic.
    * Trigonometric and Logarithmic functions.
    * Aggregation functions (`sum`, `mean`, `median`, `std`, `var`, `min`, `max`, `cumsum`).
    * Exponential and power functions (`exp`, `sqrt`).
    * Broadcasting rules and examples.
    * Logical functions (`>`, `<`, `==`, `all`, `any`).
* **Sorting, Searching, and Counting:**
    * Sorting arrays (`sort`, `np.sort`, axis).
    * Searching (`where`, `argmax`, `argmin`).
    * Counting (`count_nonzero`, `unique`).
* **Linear Algebra (`linalg` module):**
    * Matrix Multiplication (`matmul`, `@`).
    * Trace (`trace`).
    * Determinant (`det`).
    * Matrix Rank (`matrix_rank`).
* **Practice Problems:** Includes exercises covering various NumPy concepts.

## Prerequisites

* Python 3.x
* NumPy library (`pip install numpy`)
* Jupyter Notebook or JupyterLab (`pip install notebook` or `pip install jupyterlab`)

## How to Use

1.  Clone this repository:
    ```bash
    git clone https://github.com/coderzaman/Data-Analysis-With-Numpy.git
    ```
2.  Navigate to the repository directory:
    ```bash
    cd Data-Analysis-With-Numpy
    ```
3.  Launch Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```
4.  Open the `Data_Analysis_With_Numpy_ipynb.ipynb` file.
5.  Run the cells to see the explanations and code outputs.

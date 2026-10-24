# Data Analysis with NumPy

A step-by-step learning repository covering the fundamentals of NumPy for numerical computing and data analysis with Python.

This repository contains practical exercises and examples covering NumPy arrays, array attributes, data types, array creation techniques, random number generation, indexing, slicing, copying, advanced indexing, and iteration.

## Table of Contents

- [About the Project](#about-the-project)
- [Learning Objectives](#learning-objectives)
- [Topics Covered](#topics-covered)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Learning Outcomes](#learning-outcomes)
- [Project Structure](#project-structure)
- [Author](#author)
- [License](#license)

## About the Project

This project is part of my journey into **Data Analysis with Python**. It focuses on learning NumPy step by step through practical examples and exercises.

NumPy is a fundamental Python library for numerical computing. It provides the powerful `ndarray` object, which supports efficient storage, manipulation, and computation on multidimensional arrays.

The goal of this repository is to build a strong foundation in NumPy before moving on to more advanced data analysis tasks using libraries such as Pandas, Matplotlib, and Seaborn.

## Learning Objectives

- Understand the fundamentals of NumPy.
- Create and manipulate one-dimensional and multidimensional arrays.
- Explore array attributes and data types.
- Create arrays using different techniques.
- Generate arrays containing random values.
- Work with numerical ranges and matrix structures.
- Access and modify array elements using indexing and slicing.
- Understand array copying and advanced indexing.
- Iterate through NumPy arrays.
- Develop a foundation for practical data analysis with Python.

## Topics Covered

### 10.1 Introduction to NumPy

- Introduction to the NumPy library.
- Importance of NumPy in numerical computing and data analysis.
- Understanding NumPy arrays.
- Basic array operations.

### 10.2 ndarray and Its Attributes

- Introduction to the `ndarray` object.
- Understanding the structure of NumPy arrays.
- Exploring important array attributes:
  - `ndim` — Number of array dimensions.
  - `shape` — Size of the array along each dimension.
  - `size` — Total number of elements.
  - `dtype` — Data type of array elements.
  - `itemsize` — Memory size of each element in bytes.
  - `nbytes` — Total memory consumed by array elements.

### 10.3 ndarray Data Type

- Understanding NumPy data types (`dtype`).
- Integer, floating-point, Boolean, and string data.
- Checking array data types.
- Specifying data types during array creation.
- Converting array elements from one data type to another using `astype()`.

### 10.4 ndarray Creation from Existing Data

- Creating arrays from Python lists.
- Creating arrays from nested lists.
- Converting existing Python sequences into NumPy arrays.
- Using `np.array()` to create arrays from existing data.
- Understanding one-dimensional and multidimensional arrays.

### 10.5 ndarray Creation from Scratch

- Creating arrays filled with zeros using `np.zeros()`.
- Creating arrays filled with ones using `np.ones()`.
- Creating arrays with a specific value using `np.full()`.
- Creating uninitialized arrays using `np.empty()`.
- Specifying array shapes and data types.

### 10.6 ndarray Generation with Random Values

- Generating random numbers with NumPy.
- Creating random floating-point values using `np.random.rand()`.
- Generating random integers using `np.random.randint()`.
- Generating random values from a normal distribution using `np.random.randn()`.
- Generating random samples using `np.random.random()`.
- Using random seeds for reproducible results.

### 10.7 ndarray Creation from Range

- Creating arrays with evenly spaced values using `np.arange()`.
- Specifying start, stop, and step values.
- Understanding the difference between Python's `range()` and NumPy's `arange()`.
- Creating sequences for numerical computations.

### 10.8 Creating Diagonal and Identity Matrices

- Creating diagonal matrices using `np.diag()`.
- Creating identity matrices using `np.eye()`.
- Creating square identity matrices using `np.identity()`.
- Understanding the structure and applications of diagonal and identity matrices.

### 10.9 ndarray Indexing and Slicing

- Accessing individual array elements.
- Using positive and negative indexing.
- Extracting elements from one-dimensional arrays.
- Selecting rows and columns from multidimensional arrays.
- Slicing arrays using start, stop, and step.
- Selecting subarrays from two-dimensional arrays.
- Modifying array elements using indexing and slicing.

### 10.10 ndarray Copy, Advanced Indexing, and Iteration

- Understanding array assignment and reference behavior.
- Creating shallow views and independent copies.
- Using `copy()` to create independent array copies.
- Understanding basic indexing versus advanced indexing.
- Selecting array elements using integer array indexing.
- Selecting elements using Boolean indexing and masks.
- Iterating through one-dimensional and multidimensional arrays.
- Using `np.nditer()` for array iteration.
- Understanding how views and copies affect array modifications.

## Technologies Used

- **Programming Language:** Python
- **Library:** NumPy
- **Development Environment:** Jupyter Notebook / Python IDE
- **Version Control:** Git
- **Code Hosting:** GitHub

## Installation

### Prerequisites

Make sure Python and pip are installed on your computer.

Check your Python installation:

```bash
python --version
```

Check pip:

```bash
pip --version
```

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/data-analysis-with-numpy.git
```

Replace `YOUR_USERNAME` with your GitHub username.

### Step 2: Navigate to the Project Directory

```bash
cd data-analysis-with-numpy
```

### Step 3: Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on macOS or Linux:

```bash
source venv/bin/activate
```

### Step 4: Install NumPy

```bash
pip install numpy
```

If you are working with Jupyter Notebook, install it using:

```bash
pip install notebook
```

## How to Run

If the examples are stored in Jupyter Notebook files (`.ipynb`), start Jupyter Notebook:

```bash
jupyter notebook
```

Open the relevant notebook and run the cells sequentially.

If the examples are stored in Python files (`.py`), run a file using:

```bash
python filename.py
```

Replace `filename.py` with the actual Python filename.

**Note:** The exact filenames and execution steps depend on the files included in this repository.

## Learning Outcomes

After completing these topics, I have practiced the following concepts:

- Creating and manipulating NumPy arrays.
- Inspecting array dimensions, shapes, sizes, and data types.
- Generating arrays using built-in NumPy functions.
- Working with random values, numerical ranges, and matrices.
- Accessing and extracting data using indexing and slicing.
- Understanding array views, copies, and advanced indexing.
- Iterating through array elements and dimensions.
- Building a foundation for data manipulation and numerical analysis with Python.

## Project Structure

The repository is organized around the topics covered in the learning modules.

An example structure is shown below:

```text
data-analysis-with-numpy/
│
├── 10.1_intro_to_numpy.ipynb
├── 10.2_ndarray_and_attributes.ipynb
├── 10.3_ndarray_data_type.ipynb
├── 10.4_array_creation_from_existing_data.ipynb
├── 10.5_array_creation_from_scratch.ipynb
├── 10.6_random_array_generation.ipynb
├── 10.7_array_creation_from_range.ipynb
├── 10.8_diagonal_and_identity_matrix.ipynb
├── 10.9_ndarray_indexing_and_slicing.ipynb
├── 10.10_copy_advanced_indexing_and_iteration.ipynb
└── README.md
```

**Note:** This is a suggested structure. Update the filenames in this section to match your actual repository files.

## Author

* * *
**Abdul Ahad Chowdhury**
- GitHub: [@ahad987](https://github.com/ahad987)
- Email: [ahad987@gmail.com](mailto:ahad987@gmail.com)
- **LinkedIn:** [linkedin.com/in/ahad1987](https://www.linkedin.com/in/ahad1987/)
- **Facebook:** [@ahadc](https://facebook.com/ahadc)
- **WhatsApp:** [Message on WhatsApp](https://wa.me/ahad_987/)
- **Phone:** [+8801812148778](tel:+8801812148778)
- Project: [https://github.com/ahad987/AI-ML-Module-10-Data-Analysis-with-NumPy](https://github.com/ahad987/AI-ML-Module-10-Data-Analysis-with-NumPy)

**Abdul Ahad Chowdhury**

Computer Programmer | Python Developer | Data Analysis Learner

GitHub: [Abdul Ahad Chowdhury](https://github.com/ahad987)

## License

This repository is intended for learning, practice, and educational purposes.

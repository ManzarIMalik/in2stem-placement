# In2Stem Placement at University of Salford for AI & Data Science Learning

This repository contains a collection of Jupyter notebooks designed for learning and exploring fundamental concepts in Natural Language Processing (NLP), Python programming, and Data Science. These notebooks are publicly shared for educational purposes and personal development.

---

## 📚 Notebooks Overview

### 1. Intro_to_NLP.ipynb
This notebook provides an introduction to Natural Language Processing (NLP). It covers:
* **What is NLP?** - Definition, intersection with computer science, AI, and linguistics, and challenges of human language (ambiguity, context, sarcasm/irony).
* **Strings** - Fundamental concepts of strings in Python, including creation using single, double, and triple quotes.
* **String Indexing and Slicing** - How to access parts of a string using indexing (starting at 0) and slicing (`[start:end]`).
* **String Methods** - Important built-in string functions like `.lower()`, `.upper()`, `.strip()`, `.replace()`, `.split()`, and `.join()` for text cleaning and manipulation.
* **F-Strings** - A simple and readable way to embed expressions within string literals.
* **Journey to NLP (NLTK)** - Introduction to NLTK (Natural Language Toolkit) as a foundational library for language processing.
* **Exploratory Data Analysis (EDA) Example** - Demonstrates loading and basic exploration of a Kaggle dataset (`tripadvisor_hotel_reviews.csv`) using Pandas, including checking for null values and adding a review length column. It also visualizes the distribution of review lengths using a histogram and generates a WordCloud.

### 2. Learning_Python_In2Stem_Placement.ipynb
This notebook offers an interactive guide to learning Python basics, covering:
* **First Program** - A classic "Hello World!" example.
* **Different Types of Comments** - Explains single-line (`#`), multi-line (using multiple `#` or triple quotes), and in-line comments.
* **Arithmetic Operations** - Covers basic operations like addition, subtraction, multiplication, division (including quotient `//` and remainder `%`), and exponentiation (`**`), emphasizing the PEDMAS rule. Includes an interactive widget to experiment with arithmetic.
* **Boolean Operations** - Demonstrates comparison operators (`>`, `<`, `<=`, `>=`, `==`, `!=`) and logical operators (`and`, `or`, `not`). Features an interactive widget for boolean operations.
* **Importing Libraries** - How to import modules (`import math as m`, `from math import tau`) and use `help()` and `keyword.kwlist`.
* **type()** - Explains how to use `type()` to determine the data type of various objects (int, float, str, bool, list, tuple, set, dict).
* **Data Types and Structures** - Overview of Python's built-in data structures (List, dictionary, tuple, set), differentiating between mutable and immutable types.
    * **Strings**: Creation, comparison, length (`len()`), `in` operator, indexing, slicing, escape sequences (`\n`, `\t`), multi-line strings using triple quotes, multiplication, concatenation, and various string functions (`.upper()`, `.lower()`, `.capitalize()`, `.title()`, `.replace()`, `.count()`, `.split()`, `.find()`, `.index()`, `.startswith()`, `.endswith()`, `.lstrip()`, `.rstrip()`, `.strip()`, `.swapcase()`, `.isalnum()`, `.isnumeric()`, `.isalpha()`, `.islower()`, `.isupper()`, `.istitle()`, `.isspace()`).
    * **Lists**: Creation, concatenation, multiplication, `min()`, `max()`, `sum()`, `append()`, `extend()`, `pop()`, `insert()`, accessing elements by index (including nested lists and slicing), `count()`, `index()`, `remove()`, `reverse()`, and `sort()`. Includes an interactive widget for list manipulation.
    * **Tuples**: Similar to lists but immutable, defined using `()`, and functions like `count()`, `index()`, `sum()`, `len()`, `sorted()`, `reversed()`, and tuple unpacking. Includes an interactive widget to access tuple elements.
    * **Dictionaries**: Defined by key-value pairs `{}`, mutable, unique and immutable keys, adding/updating pairs, accessing `.keys()`, `.values()`, and `.items()`, and converting from tuples. Includes an interactive widget for dictionary manipulation.
    * **Sets**: Contains unique elements, adding (`.add()`), removing (`.remove()`, `.discard()`), copying (`.copy()`), and clearing (`.clear()`) elements, and converting between lists and sets. Demonstrates set operations like union, intersection, difference, and symmetric difference.
* **isinstance()** - Checks the type of an object.
* **Explicit Type Conversion (Type Casting)** - How to convert between data types using constructors like `int()`, `str()`, `float()`, `bool()`, `list()`, and `tuple()`.
* **Advanced Numbers** - Covers octal (`0o`), hexadecimal (`0x`), binary (`0b`), and complex numbers.
* **Input at Runtime** - Using the `input()` function to get user input and converting it to different data types.
* **Conditional Statements** - `if-else` and `elif` statements, emphasizing indentation.
* **range()** - Generates sequences of numbers.
* **For Loop** - Iterating over lists and using list, dictionary, and set comprehensions.
* **enumerate()** - Yields (index, value) tuples during iteration.
* **While Loop** - Basic `while` loop usage and a data cleaning example.
* **Break and Continue Statements** - Controls loop execution flow.
* **Creating Functions using `def`** - Function definition, parameters, return statements, and documentation. Includes examples like data cleaning and list summation within functions, and histogram creation using dictionaries.
* **Lambda Statement** - Creating small anonymous functions.
* **join()** - Joins a list of strings.
* **Error Handling (try-except-finally)** - Managing runtime errors.
* **Iterator** - Using `iter()` and `next()` for iterable objects.
* **Generators** - Lazily evaluated iterators using `yield`.
* **Decorator** - Modifying function behavior with decorators, including multiple decorators and memoization.
* **Objects and Classes** - Concepts of classes, objects, attributes, methods, `self`, `__init__`, and `dir()`.
    * **Encapsulation**: Protected (`_`) and private (`__`) members, and name mangling.
    * **Special Methods**: `__init__` and `__str__`.
* **Inheritance** - Creating subclasses and understanding Method Resolution Order (MRO).
* **Python Challenges**: Includes several coding challenges to apply learned concepts, such as a guessing game, grade calculator, even/odd checker, leap year checker, and a password validator (partially implemented).

### 3. Intro_to_Data_Science_with_Python.ipynb
This notebook introduces the field of Data Science and its application using Python. It covers:
* **What is Data Science?** - Definition and its interdisciplinary nature.
* **Why Python for Data Science?** - Highlights Python's simplicity, vast libraries (NumPy, Pandas, Matplotlib, Scikit-learn), and strong community support.
* **The Data Science Workflow** - Outlines typical project steps: Data Collection, Data Cleaning and Preprocessing (where Pandas is key), Exploratory Data Analysis (EDA), Modeling, Evaluation, and Communication.
* **Other Tools for Data Science (Visualization)** - Mentions tools like Power BI, Excel/Spreadsheets, Google Looker Studio, and Tableau.
* **Numerical Python (NumPy)** - Introduction to NumPy as the fundamental package for scientific computing, focusing on the `ndarray` object and its efficiency. Demonstrates creating 1D, 2D, and arrays of zeros/ones.
* **Array Attributes and Basic Operations** - Explains `ndim`, `shape`, `size`, and `dtype` attributes of NumPy arrays.
* **Significance of Using NumPy** - Discusses efficient storage, mathematical operations, linear algebra, data preprocessing, and manipulation.
* **Pandas** - Introduces Series (1D labeled arrays) and DataFrames (2D labeled data structures).
    * **Series Creation**: Examples of creating Series from lists, including handling `np.nan`.
    * **DataFrame Creation**: Example of creating a DataFrame from a dictionary.
    * **Reading Data**: How to load CSV files into a DataFrame (`pd.read_csv()`) and inspect basic information (`.info()`, `.head()`, `.tail()`, `.describe()`).
    * **Data Cleaning**: Example of dropping missing values (`.dropna()`).
* **Matplotlib** - Introduction to Matplotlib for data visualization.
    * **Histograms**: Plotting age distribution and review rating distribution.
    * **Bar Charts**: Visualizing gender distribution, average purchase amount by category, and average purchase amount by payment method.
    * **Pie Charts**: Showing subscription status distribution.
    * **Top Items**: Displaying the top 10 purchased items in a bar chart.

---

## 🚀 Getting Started

To use these notebooks, ensure you have Jupyter Notebooks installed. You can install the necessary libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn nltk ipywidgets wordcloud
```

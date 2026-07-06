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
* **Preprocessing** - Common text cleaning steps applied before analysis.
* **Sentiment Analysis** - Scoring review sentiment with NLTK's VADER (`SentimentIntensityAnalyzer`) and labeling reviews as positive/negative/neutral.
* **Large Language Models** - Using Google's Gemini API (`google-genai`) for text generation, streaming responses, and building a simple chat loop with a system instruction.
* **Homework** - Chatbot-building exercises using the Gemini API (e.g. an "EmojiBot" and two chatbots of your choice).

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
    * **Frozensets**: Immutable sets and how they differ from regular sets.
* **isinstance()** - Checks the type of an object.
* **Explicit Type Conversion (Type Casting)** - How to convert between data types using constructors like `int()`, `str()`, `float()`, `bool()`, `list()`, and `tuple()`.
* **Advanced Numbers** - Covers octal (`0o`), hexadecimal (`0x`), binary (`0b`), and complex numbers.
* **Multiple Variables Assignment** - Assigning several variables in a single statement.
* **`is` Statement and `id()`** - Identity comparison versus equality comparison.
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
* **Other Built-ins** - `pow()`, `abs()`, `round()`, `divmod()`, `zip()`, `map()`, `filter()`, `reduce()`, and `all()`/`any()`.
* **Reading and Writing Files** - Basic file I/O.
* **Error Handling (try-except-finally)** - Managing runtime errors, the built-in exception hierarchy, and creating user-defined exceptions.
* **Iterator** - Using `iter()` and `next()` for iterable objects.
* **Generators** - Lazily evaluated iterators using `yield`.
* **Decorator** - Modifying function behavior with decorators, including multiple decorators and memoization.
* **Objects and Classes** - Concepts of classes, objects, attributes, methods, `self`, `__init__`, and `dir()`.
    * **Encapsulation**: Protected (`_`) and private (`__`) members, and name mangling.
    * **Special Methods**: `__init__` and `__str__`.
* **Inheritance** - Creating subclasses and understanding Method Resolution Order (MRO), `issubclass()`, and `super()`.
* **Polymorphism** and **Abstraction** - Core OOP concepts, including abstract base classes.
* **`@property`, `@staticmethod`, `@classmethod`** - Built-in decorators for managing attribute access and alternative constructors.
* **Modules, Libraries and Packages** - Organizing code, including subpackages.
* **Miscellaneous** - `*args` & `**kwargs`, the `_` placeholder, the `^` XOR operator, `ord()`, colored terminal text (`termcolor`), `Enum`, `nonlocal`/`global`, and debugging with the Python Debugger (`pdb`).
* **Python Challenges**: Five pair-programming coding challenges to apply learned concepts:
    1. Ask for and greet the user by name.
    2. A simple calculator (+, -, *, /).
    3. A Celsius/Fahrenheit temperature converter.
    4. A score-to-letter-grade calculator.
    5. A password validator with strict conditions (length, uppercase, lowercase, number, special character).

### 3. Intro_to_computer_vision.ipynb
This is a full-length (~3 hour) standalone introduction to Computer Vision, building gradually from first principles up to modern deep learning, with interactive widgets and "try it yourself" exercises woven throughout - organised the same way as `Intro_to_NLP.ipynb` (plain, unnumbered headings, no separate objectives/table-of-contents section). It covers:
* **Images as Data**: Pixels as numbers (with an interactive R/G/B channel viewer), RGB vs. HSV color spaces (with an interactive color-masking exercise using `cv2.inRange`), grayscale conversion, manual and automatic (Otsu) thresholding.
* **Classical Image Processing**: Hand-written and built-in convolution filters (blur/sharpen), Sobel gradients and interactive Canny edge detection, morphological operations (erosion/dilation/opening/closing), geometric transforms (rotation, scaling, perspective correction), contour-based shape counting, and ORB feature matching between a rotated image pair.
* **Bridging to Deep Learning**: A from-scratch NumPy convolution + max-pooling implementation to demystify how CNN layers work before using pretrained networks.
* **Modern Computer Vision with YOLO11**: Image classification, object detection (with an IoU worked example and confidence-threshold widget), pose estimation (with keypoint-angle calculations), image segmentation (`yolo11n-seg` and FastSAM), and multi-object tracking on a synthetically generated video, plus pointers to SAM 3, RT-DETR, and Oriented Bounding Boxes (OBB) for further exploration.
* **The Hugging Face Model Hub**: Using `transformers` pipelines to run community models from [huggingface.co/models](https://huggingface.co/models) - image classification (ViT), zero-shot classification (CLIP), and object detection (DETR) - compared against the YOLO11 results.
* **Fine-Tuning a Model**: A quick, in-class transfer-learning demo fine-tuning `yolo11n-cls` on the tiny MNIST160 dataset.
* **Real-World Mini Projects**: Colab webcam capture, an interactive object counter, a privacy face/person blurrer, and an Instagram-style photo filter picker.
* **Bonus: Generative Vision** (optional, GPU) - Text-to-image generation with Stable Diffusion.
* **Homework** - Ten tiered exercises (warm-up, core, and stretch) applying the above tasks to your own photos.

### 4. Intro_to_Data_Science_with_Python.ipynb
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
* **Homework** - Find your own dataset on Kaggle, load it with Pandas, explore it, and visualize it with Matplotlib. Includes a sample solution analyzing football match results.

---

## 🚀 Getting Started

These notebooks are designed to be run in **Google Colab** - just open a notebook and click Run. Colab already has NumPy, Pandas, Matplotlib, and OpenCV installed; each notebook installs any other libraries it needs (NLTK, `ipywidgets`, `wordcloud`, `termcolor`, `google-genai`, `ultralytics`, `transformers`) in its own cells.

A couple of things to set up before running:
* **Datasets**: The EDA/data cells in `Intro_to_NLP.ipynb` and `Intro_to_Data_Science_with_Python.ipynb` expect files uploaded to `/content/` in your Colab session (e.g. `tripadvisor_hotel_reviews.csv`, `shopping_trends.csv`). Download the dataset from Kaggle and upload it to your Colab session's file browser first, using the same filename referenced in the notebook. `Intro_to_computer_vision.ipynb` downloads its sample images directly by URL, so no manual upload is needed unless you want to try the exercises on your own photo.
* **Gemini API key** (`Intro_to_NLP.ipynb` only): The "Large Language Models" section calls the Gemini API and reads the key via Colab's secrets manager. Get a free API key from [ai.dev](https://ai.dev), then in Colab open the 🔑 **Secrets** tab (left sidebar) and add it as `GOOGLE_API_KEY`, enabling notebook access.
* **GPU runtime** (`Intro_to_computer_vision.ipynb` bonus section only): The optional Stable Diffusion text-to-image section needs a GPU. In Colab go to **Runtime > Change runtime type** and select a GPU (e.g. T4).
* **Webcam access** (`Intro_to_computer_vision.ipynb` mini-projects section only): The webcam-capture cell needs browser camera permission and only works in Colab (not locally) - it's entirely optional and the rest of the notebook works fine without it.

If you'd rather run a notebook locally instead of in Colab, install the libraries with pip and replace the `/content/...` paths with your local file paths:

```bash
pip install numpy pandas matplotlib nltk ipywidgets wordcloud termcolor google-genai opencv-python ultralytics transformers
```

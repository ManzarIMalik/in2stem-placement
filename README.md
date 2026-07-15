# In2Stem Placement at University of Salford for AI & Data Science Learning

A collection of Jupyter notebooks for learning Computer Science, Python, Data Science, NLP, and Computer Vision - shared for educational purposes.

## Notebooks

1. **Intro_to_NLP.ipynb** - Natural Language Processing from strings to LLMs: string handling, an EDA walkthrough on 20k real hotel reviews, preprocessing with NLTK (tokenization, stop words, POS-aware lemmatization), turning words into numbers with Bag of Words and TF-IDF, sentiment analysis with VADER, training a text classifier with scikit-learn, and using the Gemini API to build chatbots.
2. **Learning_Python_In2Stem_Placement.ipynb** - A full Python fundamentals course: syntax, data structures, control flow, functions, OOP, and more, with interactive widgets and coding challenges throughout.
3. **Intro_to_computer_vision.ipynb** - A full-length introduction to Computer Vision: images as data, classical image processing, YOLO11 (classification, detection, pose, segmentation, tracking), Hugging Face model pipelines, fine-tuning, mini projects, and a generative vision bonus section.
4. **Intro_to_Data_Science_with_Python.ipynb** - The data science workflow end to end on 3,900 real customer purchases: NumPy arrays and vectorization, Pandas for loading, cleaning, filtering and grouping, and Matplotlib for visualizing. Then the part most tutorials skip - telling a real finding from a convincing-looking one, using shuffle tests, honest error bars, and a baseline the model has to beat.
5. **Intro_to_Computer_Science_and_AI.ipynb** - The conceptual foundation the others build on, and a good place to start: binary and algorithms, Big-O, data structures, the branches of the field, then AI from Turing and the perceptron through both AI winters to machine learning, neural networks built from scratch, transformers, and generative models.

## Getting Started

Run these in **Google Colab** - just open a notebook and click Run. Colab already has NumPy, Pandas, Matplotlib, scikit-learn, and OpenCV installed; each notebook installs anything else it needs (NLTK, `ipywidgets`, `wordcloud`, `termcolor`, `google-genai`, `ultralytics`, `transformers`) in its own cells.

A few things to set up first:
* **Nothing at all** (`Intro_to_Computer_Science_and_AI.ipynb`): no dataset, no API key, no GPU. It runs top to bottom on a free CPU runtime, so it's the easiest one to start with.
* **Datasets**: nothing to upload. `Intro_to_Data_Science_with_Python.ipynb`, `Intro_to_NLP.ipynb`, and `Intro_to_computer_vision.ipynb` all download their own data, so they run top to bottom as-is - you only need your own file if you want to try the homework on a dataset you picked.
* **Gemini API key** (`Intro_to_NLP.ipynb` only): get a free key from [ai.dev](https://ai.dev), then add it as `GOOGLE_API_KEY` in Colab's 🔑 Secrets tab.
* **GPU runtime** (`Intro_to_computer_vision.ipynb` bonus section only): the optional Stable Diffusion section needs a GPU - **Runtime > Change runtime type > T4 GPU**.
* **Webcam access** (`Intro_to_computer_vision.ipynb` mini-projects only): optional, needs browser camera permission, Colab-only.

To run locally instead, install the libraries with pip and swap `/content/...` paths for local file paths:

```bash
pip install numpy pandas matplotlib scikit-learn nltk ipywidgets wordcloud termcolor google-genai opencv-python ultralytics transformers torch
```

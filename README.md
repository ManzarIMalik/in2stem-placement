# In2Stem Placement at University of Salford for AI & Data Science Learning

A collection of Jupyter notebooks for learning Python, Data Science, NLP, and Computer Vision - shared for educational purposes.

## Notebooks

1. **Intro_to_NLP.ipynb** - Natural Language Processing basics: strings, NLTK, an EDA + sentiment analysis walkthrough, and using the Gemini API to build simple chatbots.
2. **Learning_Python_In2Stem_Placement.ipynb** - A full Python fundamentals course: syntax, data structures, control flow, functions, OOP, and more, with interactive widgets and coding challenges throughout.
3. **Intro_to_computer_vision.ipynb** - A full-length introduction to Computer Vision: images as data, classical image processing, YOLO11 (classification, detection, pose, segmentation, tracking), Hugging Face model pipelines, fine-tuning, mini projects, and a generative vision bonus section.
4. **Intro_to_Data_Science_with_Python.ipynb** - An introduction to the data science workflow using NumPy, Pandas, and Matplotlib for cleaning, exploring, and visualizing data.

## Getting Started

Run these in **Google Colab** - just open a notebook and click Run. Colab already has NumPy, Pandas, Matplotlib, and OpenCV installed; each notebook installs anything else it needs (NLTK, `ipywidgets`, `wordcloud`, `termcolor`, `google-genai`, `ultralytics`, `transformers`) in its own cells.

A few things to set up first:
* **Datasets**: `Intro_to_NLP.ipynb` and `Intro_to_Data_Science_with_Python.ipynb` expect a CSV uploaded to `/content/` (e.g. `tripadvisor_hotel_reviews.csv`, `shopping_trends.csv`) - download from Kaggle and upload via Colab's file browser. `Intro_to_computer_vision.ipynb` downloads its own sample images, so no upload is needed unless you want to try the exercises on your own photo.
* **Gemini API key** (`Intro_to_NLP.ipynb` only): get a free key from [ai.dev](https://ai.dev), then add it as `GOOGLE_API_KEY` in Colab's 🔑 Secrets tab.
* **GPU runtime** (`Intro_to_computer_vision.ipynb` bonus section only): the optional Stable Diffusion section needs a GPU - **Runtime > Change runtime type > T4 GPU**.
* **Webcam access** (`Intro_to_computer_vision.ipynb` mini-projects only): optional, needs browser camera permission, Colab-only.

To run locally instead, install the libraries with pip and swap `/content/...` paths for local file paths:

```bash
pip install numpy pandas matplotlib nltk ipywidgets wordcloud termcolor google-genai opencv-python ultralytics transformers
```

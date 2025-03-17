# Audible Dataset Analysis

## 📌 Overview

This project analyzes an audiobook dataset downloaded from Audible.in, covering releases from 1998 to 2025. The dataset includes various audiobook attributes, such as title, author, narrator, duration, release date, language, ratings, and price.

## 📂 Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/snehangsude/audible-dataset) and contains the following columns:

- **name**: The audiobook's title.
- **author**: The author's name.
- **narrator**: The audiobook's narrator.
- **time**: Duration in hours and minutes.
- **releasedate**: Date of release.
- **language**: Language of the audiobook.
- **stars**: Average rating (out of 5) and the number of ratings.
- **price**: Price in INR (Indian Rupee).

## 📊 Steps in the Notebook

### 1️⃣ Data Loading

- Load the dataset (`audible_uncleaned.csv`) using `pandas`.
- Display the first few rows to inspect the structure.

### 2️⃣ Data Inspection

- Use `.info()` to examine column data types and check for missing values.

### 3️⃣ Data Cleaning

- Handle missing values and inconsistencies.
- Convert data types if necessary.

### 4️⃣ Exploratory Data Analysis (EDA)

- Summary statistics of audiobook prices and ratings.
- Visualization of trends using `matplotlib`.

## 🛠️ Requirements

Ensure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib
```

## 🚀 Usage

Run the Jupyter Notebook (`notebook.ipynb`) step by step to analyze the dataset:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

audible = pd.read_csv("audible_uncleaned.csv")
audible.info()
```

## 📌 Conclusion

This project provides insights into the audiobook market, helping to understand trends in pricing, ratings, and release patterns. Further analysis can explore audiobook popularity by author or language.

## 🔗 References

- Dataset: [Kaggle - Audible Dataset](https://www.kaggle.com/datasets/snehangsude/audible-dataset)
- Pandas Documentation: [pandas.pydata.org](https://pandas.pydata.org/)

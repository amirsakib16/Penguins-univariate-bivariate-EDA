# Penguins Univariate & Bivariate EDA

Exploratory Data Analysis (Univariate + Bivariate) on the famous **Palmer Penguins** dataset.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4B8BBE)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## Full Report (PDF)

| Action | Button |
|--------|--------|
| **Download PDF** | [![Download PDF](https://img.shields.io/badge/Download-PDF_Report-red?style=for-the-badge)](https://drive.google.com/file/d/1mCeDK7wQoEVWz7Rx65sTuoGF__iFXz2W/view?usp=sharing) |
| **Preview PDF** | [![Preview PDF](https://img.shields.io/badge/Preview-PDF_Report-blue?style=for-the-badge)](https://drive.google.com/file/d/1mCeDK7wQoEVWz7Rx65sTuoGF__iFXz2W/view?usp=sharing) |

> Click **Preview** to view the report directly on GitHub, or **Download** to save it locally.

---

## Dataset

- **Source**: [Palmer Penguins Dataset for EDA (Kaggle)](https://www.kaggle.com/datasets/satyajeetrai/palmer-penguins-dataset-for-eda)
- **Size**: 344 rows × 9 columns
- **Species**: Adelie, Chinstrap, Gentoo
- **Islands**: Biscoe, Dream, Torgersen

**Analysis Notebook**:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JGWzkmzex85tIklt3VHrRJxZAQnkEGx5?usp=sharing)

---

## Key Insights

### Univariate Analysis
- **Species**: Adelie is the most frequent (152)
- **Island**: Biscoe has the highest count (168)
- **Sex**: Almost balanced (slightly more males)
- All continuous variables (bill length/depth, flipper length, body mass) are **approximately symmetric** or only **mildly skewed**
- **No outliers** detected using IQR method
- Very few missing values (mainly in `sex`)

### Bivariate Analysis
- Strong species–island association (Gentoo almost exclusive to Biscoe)
- Clear separation of species in bill length vs bill depth space
- Positive relationship between bill length and body mass
- Gentoo penguins are the heaviest with the shallowest bills

---

## All Graphs & Visualizations

### 1. Univariate Distributions & Skewness
### 2. Box Plots (Outlier Detection)
### 3. Bivariate Crosstabs & Heatmaps
### 4. KDE: Bill Length vs Bill Depth (by Species & Sex)
### 5. KDE: Bill Length vs Bill Depth (by Island) & Bill Length vs Body Mass (by Species)
### 6. KDE: Bill Length vs Body Mass (by Sex) & Bill Depth vs Body Mass (by Species)
### 7. KDE: Bill Depth vs Body Mass (by Sex)
---

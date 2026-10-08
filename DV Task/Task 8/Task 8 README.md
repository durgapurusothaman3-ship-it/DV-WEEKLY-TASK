# Student Performance Data Visualization

## Project Overview

This project focuses on analyzing and visualizing student performance data using Python.

The main purpose is to understand the relationships between **Math, Reading, and Writing scores** using scatter plots and a correlation heatmap.

## Dataset

The dataset used is:

`studentperformance_preprocessed.csv`

The important columns used are:

- Math Score
- Reading Score
- Writing Score

## Objective

The objectives of this task are:

1. Create scatter plots between Math, Reading, and Writing scores.
2. Identify the relationship between different subject scores.
3. Create a correlation heatmap.
4. Understand the strength of correlation between the subjects.

## Tools and Technologies

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Visualizations

### 1. Math Score vs Reading Score

A scatter plot is created to identify the relationship between Math and Reading scores.

### 2. Math Score vs Writing Score

A scatter plot is created to identify the relationship between Math and Writing scores.

### 3. Reading Score vs Writing Score

A scatter plot is created to identify the relationship between Reading and Writing scores.

### 4. Correlation Heatmap

A correlation heatmap is created to show the correlation between:

- Math Score
- Reading Score
- Writing Score

Correlation values range from **-1 to +1**.

- `+1` → Strong positive correlation
- `0` → No correlation
- `-1` → Strong negative correlation

## Methodology

### Step 1: Import Libraries

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

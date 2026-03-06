# CSV Data Exploration with Python (Google Colab)

This project demonstrates how to load and quickly explore a CSV dataset using **Python** and **Pandas** in Google Colab.

## Features

* Read a CSV file
* View the first rows of the dataset
* View the last rows of the dataset
* Check for missing values

## Requirements

* Python
* Pandas
* Google Colab

## Usage

### 1. Import Pandas

```python
import pandas as pd
```

### 2. Load the CSV file

```python
df = pd.read_csv("your_file.csv")
```

### 3. View the first rows

```python
df.head()
```

### 4. View the last rows

```python
df.tail()
```

### 5. Check for missing values

```python
df.isnull().sum()
```

## Summary

This notebook provides a simple way to perform **basic data exploration** on a CSV file before starting data cleaning or analysis.

# Datasets-shoping-app
# 📊 Basic Data Exploration and Cleaning using Pandas

## 🚀 Project Overview

This project demonstrates the fundamentals of **Data Exploration** and **Data Cleaning** using **Python Pandas** on an Ecommerce Dataset. The dataset contains information about products, pricing, ratings, customer reviews, seller details, and more.

The goal of this project is to understand the dataset, clean the data, and prepare it for further analysis.

---

## 🎯 Objectives

✅ Load a CSV dataset into a Pandas DataFrame

✅ Explore the dataset structure

✅ Check and handle missing values

✅ Remove duplicate records

✅ Create a derived feature

✅ Generate summary statistics

✅ Export the cleaned dataset

---

## 📁 Dataset Information

| Attribute      | Value                                         |
| -------------- | --------------------------------------------- |
| Dataset Name   | Ecommerce Dataset (Products & Sizes Included) |
| Total Records  | 1000                                          |
| Total Features | 24                                            |
| Source         | Kaggle                                        |

---

## 🛠️ Technologies Used

* 🐍 Python 3
* 🐼 Pandas
* 📓 Jupyter Notebook
* 🌐 GitHub

---

## 📌 Steps Performed

### 1️⃣ Data Loading

Loaded the dataset using Pandas:

```python
import pandas as pd

df = pd.read_csv("Combined_dataset.csv")
```

---

### 2️⃣ Data Exploration

Explored dataset using:

* `head()`
* `tail()`
* `shape`
* `columns`
* `dtypes`

---

### 3️⃣ Missing Value Analysis

Checked missing values in each column:

```python
df.isnull().sum()
```

---

### 4️⃣ Data Cleaning

Removed duplicate records:

```python
df.drop_duplicates(inplace=True)
```

---

### 5️⃣ Feature Engineering

Created a derived column:

```python
df["price_difference"] = df["initial_price"] - df["final_price"]
```

---

### 6️⃣ Statistical Summary

Generated descriptive statistics:

```python
df.describe()
```

---

### 7️⃣ Export Cleaned Dataset

Saved the cleaned dataset:

```python
df.to_csv("cleaned_dataset.csv", index=False)
```

---

## 📈 Sample Dataset Information

```text
Dataset Shape: (1000, 24)
```

### Sample Columns

* product_id
* title
* product_description
* rating
* ratings_count
* initial_price
* final_price
* seller_name
* category

and many more...

---

## 📂 Project Structure

```text
basic-data-cleaning-pandas/
│
├── Basic_Data_Cleaning.ipynb
├── cleaned_dataset.csv
├── README.md
└── Combined_dataset.csv
```

---

## ✨ Key Learnings

🔹 Data Loading with Pandas

🔹 Data Exploration Techniques

🔹 Missing Value Detection

🔹 Duplicate Removal

🔹 Feature Engineering

🔹 Data Exporting

🔹 GitHub Project Management

---

## 🎉 Conclusion

This project successfully demonstrates the basic workflow of data preprocessing and cleaning using Pandas. The cleaned dataset can be used for further analysis, visualization, and machine learning applications.

⭐ If you found this project useful, feel free to star the repository!


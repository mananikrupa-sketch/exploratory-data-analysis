# Task 2 - Exploratory Data Analysis (EDA) on Housing Dataset

## Objective

The objective of this task is to perform Exploratory Data Analysis (EDA) on a cleaned housing dataset to understand the data through statistical analysis and visualizations. The analysis helps identify patterns, trends, relationships, and anomalies in the dataset.

---

## Dataset

**Dataset Used:** Cleaned Housing Dataset

The dataset contains housing price and income-related indicators across different countries and years.

### Features

* country
* iso
* year
* house_price_index
* personal_disposable_income
* real_house_price_index
* real_personal_disposable_income
* affordability_proxy
* country_encoded
* iso_encoded

---

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

Task-2-EDA-Housing/

├── dataset/
│   └── cleaned_housing_data.csv
│
├── notebook/
│   └── eda_housing.ipynb
│
├── screenshots/
│
├── README.md
│
├── requirements.txt
│
└── .gitignore

---

## Steps Performed

### 1. Data Loading

* Loaded the cleaned housing dataset using Pandas.

### 2. Dataset Inspection

* Examined dataset dimensions.
* Displayed column names.
* Checked data types and dataset information.

### 3. Missing Value Analysis

* Verified that no missing values were present in the dataset.

### 4. Summary Statistics

Generated descriptive statistics including:

* Mean
* Median
* Standard Deviation
* Minimum Value
* Maximum Value

### 5. Histograms

Created histograms to understand the distribution of numerical features.

### 6. Boxplots

Generated boxplots to identify outliers and understand data spread.

### 7. Correlation Analysis

Created a correlation matrix using a heatmap to identify relationships between numerical variables.

### 8. Pairplot Analysis

Used pairplots to visualize feature interactions and relationships.

### 9. Trend Analysis

Analyzed housing price trends across years using line plots.

### 10. Scatter Plot Analysis

Explored the relationship between disposable income and housing prices.

### 11. Anomaly Detection

Detected unusual observations (outliers) using boxplots and distribution analysis.

### 12. Feature-Level Inference

Derived meaningful insights from the visualizations and statistical summaries.

---

## Key Findings

* Housing prices vary significantly across countries and years.
* Disposable income shows a positive relationship with housing prices.
* Real house price index is strongly related to house price index.
* Some observations contain extreme values that appear as outliers.
* Housing affordability differs across observations.
* Several numerical variables show strong positive correlations.

---

## Visualizations Included

* Histograms
* Boxplots
* Correlation Heatmap
* Pairplot
* Line Plot
* Scatter Plot

---

## Conclusion

Exploratory Data Analysis was successfully performed on the housing dataset. Statistical summaries and visualizations helped identify patterns, trends, correlations, and anomalies within the data. The analysis provides valuable insights into housing prices, income levels, and affordability indicators across different countries and years.

---

## Requirements

Install the required libraries using:

pip install -r requirements.txt

---

## Author

Krupa Manani

AI & ML Internship - Task 2

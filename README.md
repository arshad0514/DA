# 🏠 House Price Analysis using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a House Price dataset using Python. The goal is to understand the factors that influence house prices and identify relationships between different housing features such as area, bedrooms, location score, and age.

## 📊 Dataset Information

The dataset contains **500 house records** and **7 features**:

| Feature        | Description                      |
| -------------- | -------------------------------- |
| Area           | Size of the house (sq.ft.)       |
| Bedrooms       | Number of bedrooms               |
| Bathrooms      | Number of bathrooms              |
| Floors         | Number of floors                 |
| Location Score | Quality rating of location (1-9) |
| Age            | Age of the house (years)         |
| Price          | House price                      |

### Dataset Shape

* Rows: 500
* Columns: 7

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Project Structure

```text
House-Price-EDA/
│
├── house_price.csv
├── House price EDA.ipynb
├── README.md
└── images/
```

## 🔍 Data Cleaning

The dataset was checked for:

### Missing Values

```python
data.isnull().sum()
```

Result:

* No missing values found.

### Duplicate Records

```python
data.duplicated().sum()
```

Result:

* No duplicate records found.

## 📈 Exploratory Data Analysis

### 1. Area vs Price

**Visualization:** Scatter Plot

**Insight:**

* Strong positive relationship between area and price.
* Larger houses generally have higher prices.

---

### 2. Age vs Price

**Visualization:** Scatter Plot

**Insight:**

* Older houses tend to have lower prices.
* Newer properties are usually more expensive.

---

### 3. Location Score vs Price

**Visualization:** Scatter Plot

**Insight:**

* Houses in better locations generally have higher prices.

---

### 4. Area Distribution

**Visualization:** Histogram

**Insight:**

* Most houses fall within medium-to-large area ranges.

---

### 5. Bedrooms and Floors Distribution

**Visualization:** Grouped Bar Chart

**Insight:**

* Houses with more bedrooms tend to have higher floor distributions.

---

### 6. Price Distribution

**Visualization:** Box Plot

**Insight:**

* House prices are widely distributed.
* A few high-priced properties are present.

---

### 7. Bedrooms vs Price

**Visualization:** Box Plot

**Insight:**

* Houses with more bedrooms generally show higher median prices.

---

### 8. Bedroom Distribution

**Visualization:** Pie Chart

**Insight:**

* Bedroom categories are relatively balanced across the dataset.

---

### 9. Correlation Analysis

**Visualization:** Heatmap

**Insight:**

* Area has the strongest positive correlation with price.
* Location Score also positively influences price.
* Age has a negative correlation with price.

## 📊 Statistical Summary

| Metric                 | Value       |
| ---------------------- | ----------- |
| Average Area           | 2319 sq.ft  |
| Average Bedrooms       | 3           |
| Average Bathrooms      | 2           |
| Average Floors         | 1.47        |
| Average Location Score | 4.98        |
| Average House Age      | 14.95 years |
| Average Price          | ₹856,335    |

## 🔑 Key Findings

* Area is the strongest predictor of house price.
* Houses in better locations command higher prices.
* Older houses tend to be less expensive.
* More bedrooms generally increase house value.
* No missing values or duplicate records were found, indicating a clean dataset.

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/house-price-eda.git
```

### Install Required Libraries

```bash
pip install pandas matplotlib seaborn
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```text
House price EDA.ipynb
```

## 📷 Sample Visualizations

Add screenshots of:

* Scatter Plot (Area vs Price)
* Correlation Heatmap
* Bedrooms vs Price Boxplot

inside an `images/` folder and display them here.

## 📚 Learning Outcomes

Through this project, I learned:

* Data cleaning and validation
* Exploratory Data Analysis (EDA)
* Data visualization using Matplotlib and Seaborn
* Correlation analysis
* Extracting business insights from data

## 👨‍💻 Author

**Mohammed Arshad**

Aspiring Data Analyst | Python | Pandas | SQL | Tableau

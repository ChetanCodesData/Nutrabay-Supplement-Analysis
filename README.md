# 🥤 Nutrabay Supplement Analysis Project

## 📌 Project Overview

This project focuses on extracting and analyzing supplement product data from the Nutrabay website using Selenium and Python. The dataset was cleaned, transformed, and analyzed using Pandas to identify pricing trends, protein distribution, supplement categories, and business insights.

The project demonstrates web scraping, data preprocessing, exploratory data analysis (EDA), and insight generation using real-world e-commerce supplement data.

---

# 🚀 Objectives

* Extract supplement product data from the Nutrabay website
* Perform data cleaning and preprocessing using Python and Pandas
* Analyze supplement pricing trends and protein distribution
* Compare supplement categories using business metrics
* Generate customer-focused business insights
* Understand product segmentation in the nutrition industry

---

# 🛠 Tools & Technologies Used

* Python
* Pandas
* Selenium
* CSV Data Handling
* Jupyter Notebook
* VS Code

---

# 🌐 Data Collection

The dataset was collected from the Nutrabay website using Selenium automation.

### Selenium was used for:

* Automating browser interaction
* Extracting product names
* Capturing prices
* Extracting supplement categories
* Collecting protein gram values
* Handling dynamic website content

---

# 📂 Dataset Columns

| Column        | Description          |
| ------------- | -------------------- |
| Product       | Product name         |
| Price         | Product price in INR |
| Category      | Product category     |
| Supplement    | Brand/Product type   |
| Protein_grams | Protein per serving  |

---

# 🧹 Data Preprocessing

## ✅ Data Cleaning

* Removed duplicate records
* Checked missing values
* Standardized text formatting
* Converted price columns into numeric format
* Verified protein values

## 🔄 Data Transformation

* Created category-wise summaries
* Calculated average prices
* Compared protein content across supplements
* Grouped products by supplement category

---

# 📊 Exploratory Data Analysis (EDA)

## 1️⃣ Category-wise Product Distribution

Analyzed supplement categories to identify product distribution across the dataset.

### Insight

* Whey Protein products dominated the dataset.
* Omega 3 and Plant Protein categories had fewer products.

---

## 2️⃣ Price Analysis

Calculated maximum, minimum, and average prices for each category.

### Insight

* Whey Protein products had the highest pricing range.
* Omega 3 products were comparatively affordable.
* Premium supplements increased overall category averages.

---

## 3️⃣ Protein Content Analysis

Analyzed protein content per serving across supplement categories.

### Insight

* Most whey proteins contained around 24–26g protein per serving.
* Vegan and wellness products had lower protein values.
* High-protein products were mainly concentrated in the whey category.

---

## 4️⃣ Affordable vs Premium Products

Compared products across different pricing segments.

### Insight

* Nutrabay offers products for both budget and premium customers.
* Premium isolates and advanced whey blends were the most expensive.
* Budget-friendly products were mostly available in Omega 3 and basic supplements.

---

## 5️⃣ Supplement Category Comparison

Compared supplement categories using pricing and protein metrics.

### Insight

* Whey Protein provided high protein concentration with premium pricing.
* Plant-based proteins showed moderate pricing.
* Fish oil products focused more on wellness benefits than protein content.

---

# 💡 Business Insights

## Key Insights Extracted

### 1. Whey Protein is the Dominant Segment

Most products belonged to the whey protein category, showing strong customer demand in the fitness market.

### 2. Premium Products Increase Average Price

A small number of high-priced supplements significantly increased overall category averages.

### 3. Protein-rich Products Have Higher Prices

Products with higher protein concentration generally had premium pricing.

### 4. Budget Products Exist for Beginners

Affordable supplements provide entry-level options for new fitness consumers.

### 5. Product Diversity Supports Multiple Customer Segments

The dataset included products for muscle gain, wellness, vegan nutrition, and general fitness goals.

---

# 🐍 Example Pandas Operations Used

```python
# Average price by category
df.groupby('Category')['Price'].mean()

# Maximum product price
df['Price'].max()

# Category-wise product count
df['Category'].value_counts()

# Sorting products by price
df.sort_values(by='Price', ascending=False)
```

---

# ⚠ Challenges Faced

* Extracting data from dynamic website pages
* Handling inconsistent product naming
* Cleaning mixed-format data
* Managing product categorization
---

# 🎯 Project Outcome

This project successfully demonstrated:

* Web scraping using Selenium
* Data cleaning using Pandas
* Exploratory Data Analysis (EDA)
* Business insight generation
* Real-world supplement market analysis

The project helped in understanding customer-oriented product segmentation, pricing trends, and protein distribution in the sports nutrition industry.

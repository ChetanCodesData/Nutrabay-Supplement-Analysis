# 🥤 Nutrabay Supplement Analysis Project

## 📌 Project Overview

This project is based on collecting and analyzing supplement product data from the Nutrabay website using Python and Selenium.

The main goal of this project was to understand product pricing, protein content, and supplement categories by performing data cleaning and analysis using Pandas.

The project also helped in understanding real-world web scraping and data analysis workflows.

---

# 🛠 Tools Used

* Python
* Pandas
* Selenium
* Jupyter Notebook / VS Code
* CSV File Handling

---

# 🌐 Data Collection

The data was collected from the Nutrabay website using Selenium automation.

The following details were extracted:

* Product Name
* Price
* Category
* Supplement Type
* Protein Grams

Selenium was used because the website contains dynamic content that loads while scrolling.

---


# 🧹 Data Cleaning & Preprocessing

The dataset contained inconsistent formatting and required preprocessing before analysis.

The following steps were performed:

* Removed duplicate records
* Checked missing values
* Converted prices into numeric format
* Cleaned text formatting
* Verified protein values

---

# 📊 Exploratory Data Analysis (EDA)

Different types of analysis were performed on the dataset.

### Analysis Performed

* Category-wise product distribution
* Price comparison between supplements
* Protein content analysis
* Affordable vs premium product analysis
* Supplement category comparison

---

# 💡 Key Insights

* Whey Protein had the highest number of products.
* Most whey proteins contained around 24–26g protein per serving.
* Premium supplements had significantly higher prices.
* Omega 3 products were comparatively affordable.
* Different supplement categories targeted different customer needs.

---

# 🐍 Example Pandas Operations

```python id="v2ihzd"
# Average price by category
df.groupby('Category')['Price'].mean()

# Maximum product price
df['Price'].max()

# Category-wise product count
df['Category'].value_counts()

# Sort products by price
df.sort_values(by='Price', ascending=False)
```

---

# ⚠ Challenges Faced

* Extracting data from dynamic website pages
* Handling inconsistent product names
* Cleaning mixed-format data
* Managing category-wise grouping

---

# 🎯 Project Outcome

This project helped in learning:

* Web scraping using Selenium
* Data cleaning using Pandas
* Exploratory Data Analysis (EDA)
* Product pricing analysis
* Real-world data handling and business insights generation

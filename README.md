Nutrabay Supplement Analysis Project
Project Overview

This project focuses on extracting and analyzing supplement product data from the Nutrabay website using Selenium and Python. The dataset was cleaned and analyzed using Pandas to identify pricing trends, protein distribution, supplement categories, and business insights.

Tools & Technologies Used
Python
Pandas
Selenium
CSV Data Handling
Jupyter Notebook / VS Code
Data Collection

The data was collected from the Nutrabay website using Selenium automation.

Selenium was used for:
Automating browser interaction
Extracting product names
Capturing prices
Extracting supplement categories
Collecting protein gram values
Handling dynamic website content
Dataset Columns
Column	Description
Product	Product name
Price	Product price in INR
Category	Product category
Supplement	Brand/Product type
Protein_grams	Protein per serving
Data Preprocessing Performed
1. Data Cleaning
Removed duplicate records
Checked missing values
Standardized text formatting
Converted price columns into numeric format
Verified protein values
2. Data Transformation
Created category-wise summaries
Calculated average prices
Compared protein content across supplements
Grouped products by supplement category
Exploratory Data Analysis (EDA)
1. Category-wise Product Distribution

Analysis was performed to identify which supplement categories contain the highest number of products.

Insight:
Whey Protein products dominated the dataset.
Omega 3 and Plant Protein categories had fewer products.
2. Price Analysis

Maximum, minimum, and average prices were calculated for each category.

Insight:
Whey Protein products had the highest pricing range.
Omega 3 products were comparatively affordable.
Premium protein products significantly increased category averages.
3. Protein Content Analysis

Protein values per serving were analyzed.

Insight:
Most whey proteins contained around 24–26g protein per serving.
Vegan and wellness products had lower protein values.
High-protein products were concentrated in the whey category.
4. Affordable vs Premium Products

Products were categorized into affordable and premium pricing segments.

Insight:
Nutrabay offers products across multiple pricing segments.
Premium isolates and advanced whey blends were the most expensive.
Budget-friendly products existed mainly in Omega 3 and basic supplements.
5. Supplement Category Comparison

Different supplement categories were compared using pricing and protein metrics.

Insight:
Whey Protein provided high protein concentration with premium pricing.
Plant-based proteins showed moderate pricing.
Fish oil products focused more on health benefits rather than protein content.
Business Insights
Key Insights Extracted
1. Whey Protein is the Dominant Segment

Most products belonged to the whey protein category, showing strong market demand.

2. Premium Products Increase Average Price

A few high-priced supplements heavily influenced overall average pricing.

3. Protein-rich Products Have Higher Prices

Products with higher protein concentration generally had premium pricing.

4. Budget Products Exist for Beginners

Affordable supplements provide entry-level options for new fitness consumers.

5. Product Diversity Supports Different Customer Segments

The dataset showed products for muscle gain, wellness, vegan nutrition, and general fitness.

Example Pandas Operations Used
# Average price by category
 df.groupby('Category')['Price'].mean()
 
# Maximum product price
 df['Price'].max()
 
# Category-wise product count
 df['Category'].value_counts()
 
# Sorting products by price
 df.sort_values(by='Price', ascending=False)
 
Challenges Faced
Extracting data from dynamic website pages
Handling inconsistent product naming
Cleaning mixed-format data
Managing product categorization
Converting extracted values into structured format
Project Outcome

This project successfully demonstrated:

Web scraping using Selenium
Data cleaning using Pandas
Exploratory Data Analysis (EDA)
Business insight generation
Real-world supplement market analysis

The project helped in understanding customer-oriented product segmentation, pricing trends, and protein distribution in the sports nutrition industry.

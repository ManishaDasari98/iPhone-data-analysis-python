# 📱 iPhone Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing iPhone product data using Python and Pandas. The objective is to explore the dataset, clean and transform data, perform exploratory data analysis (EDA), and create visualizations to uncover meaningful insights about iPhone pricing, ratings, RAM configurations, and product distribution.

This project demonstrates practical data analysis skills that are commonly used by Data Analysts, Data Engineers, and Business Intelligence professionals.

---

## 🎯 Business Problem

Apple offers multiple iPhone models with different RAM configurations, pricing structures, ratings, and discounts. Businesses and analysts often need to understand:

- Which iPhone models are most common?
- How pricing varies across RAM variants?
- Which products receive higher customer ratings?
- What discount patterns exist across products?
- Which models dominate the marketplace?

This project answers these questions through data analysis and visualization.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- WordCloud
- Jupyter Notebook

---

## 📂 Dataset Information

The dataset contains iPhone product details such as:

| Column | Description |
|----------|------------|
| Product Name | Name of iPhone |
| Product URL | Product Link |
| Sale Price | Current Selling Price |
| MRP | Original Price |
| Number Of Ratings | Customer Rating Count |
| Star Rating | Average Product Rating |
| Ram | RAM Configuration |

---

## 📁 Repository Structure

```text
iPhone-Data-Analysis/
│
├── Dataset/
│   └── apple_products.csv
│
├── Notebook/
│   └── iPhone Data Analysis Project.ipynb
│
├── Images/
│   ├── ram_pie_chart.png
│   ├── ram_donut_chart.png
│   ├── top5_models_bar_chart.png
│   └── wordcloud.png
│
├── README.md
│
└── requirements.txt
```

---

## 📊 Project Workflow

### Step 1: Data Loading
- Imported dataset using Pandas.
- Created DataFrame for analysis.

### Step 2: Data Exploration
Performed:
- head()
- count()
- info()
- index inspection

### Step 3: RAM Analysis
- Identified unique RAM variants.
- Calculated RAM distribution.

### Step 4: Price Analysis
Calculated:
- Maximum Price
- Minimum Price
- Average Sale Price

### Step 5: String Operations
Performed:
- Uppercase conversion
- Lowercase conversion
- String slicing
- Model extraction

### Step 6: Data Filtering
Filtered:
- High-price products
- Highly-rated products

### Step 7: Data Transformation
Created calculated columns such as:
- Discounted Price

### Step 8: GroupBy Analysis
Analyzed:
- Average price by RAM

### Step 9: Pivot Table Analysis
Generated:
- Mean Price
- Maximum Price
- Minimum Price

for each RAM variant.

### Step 10: Data Combining Techniques
Practiced:
- Concat
- Merge
- Join

---

## 📈 Visualizations Created

### 1. RAM Distribution Pie Chart
Shows the percentage distribution of RAM configurations.

### 2. RAM Distribution Donut Chart
Provides a visually appealing comparison of RAM categories.

### 3. Top 5 iPhone Models Pie Chart
Shows the most frequently occurring iPhone models.

### 4. Top 5 iPhone Models Bar Chart
Compares the frequency of top-selling models.

### 5. Word Cloud
Highlights frequently occurring terms in product names.

---

## 💡 Business Insights

### Insight 1: RAM Distribution
The dataset contains multiple RAM variants, helping identify which configurations are most commonly offered in the market.

### Insight 2: Pricing Trends
Higher RAM configurations generally have higher selling prices, indicating a positive relationship between hardware specifications and pricing.

### Insight 3: Premium Product Segment
Several iPhone models belong to the premium pricing category, reflecting Apple's premium market positioning.

### Insight 4: Customer Ratings
Most products maintain strong customer ratings, indicating high customer satisfaction and brand trust.

### Insight 5: Product Popularity
The top recurring iPhone models indicate stronger market presence and availability.

### Insight 6: Discount Opportunities
Comparing MRP and Sale Price helps identify products with the largest discounts and promotional opportunities.

---

## 🚀 Skills Demonstrated

### Python
- Data manipulation
- Data transformation
- Exploratory analysis

### Pandas
- DataFrames
- Filtering
- Aggregation
- GroupBy
- Pivot Tables
- Merge Operations

### Data Analysis
- Exploratory Data Analysis (EDA)
- Business Insights Generation
- Data Cleaning
- Feature Engineering

### Data Visualization
- Pie Charts
- Donut Charts
- Bar Charts
- Word Clouds

### Analytical Thinking
- Trend Identification
- Product Comparison
- Pricing Analysis
- Customer Rating Analysis

---

## 📷 Project Screenshots

### RAM Distribution Pie Chart
<img width="486" height="502" alt="image" src="https://github.com/user-attachments/assets/2862e660-2b07-4150-aa89-fc39e2eade33" />

### RAM Distribution Donut Chart
<img width="559" height="579" alt="image" src="https://github.com/user-attachments/assets/fcab6bb9-86b5-4685-a38b-9240fd740b43" />

### Top 5 iPhone Models Pie Chart
<img width="582" height="579" alt="image" src="https://github.com/user-attachments/assets/39e53216-890a-43dc-9696-747ba85687d8" />

### Top 5 Models Bar Chart
<img width="687" height="491" alt="image" src="https://github.com/user-attachments/assets/f9a5741a-2632-4bb1-bb7b-696825af3eed" />

### Word Cloud
<img width="944" height="502" alt="image" src="https://github.com/user-attachments/assets/3f5c8f90-0b3b-4103-90cf-f8dbb1d08f04" />

---

## 🔍 Key Learnings

Through this project, I learned:

- Data Loading and Exploration
- Data Cleaning Techniques
- String Manipulation
- Data Filtering
- Feature Engineering
- GroupBy Operations
- Pivot Tables
- Merge and Join Operations
- Data Visualization
- Business Insight Generation


⭐ If you found this project useful, please consider giving it a star.


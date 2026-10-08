# Store Sales Data Analysis 📊

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on store sales data using Python.

The objective is to understand customer purchasing behavior and identify important sales patterns across gender, age group, state, marital status, occupation, product category and individual products.

The analysis uses Python libraries such as Pandas, NumPy, Matplotlib and Seaborn for data cleaning, analysis and visualization.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure of the sales dataset
- Clean and prepare the data for analysis
- Handle missing values
- Remove unnecessary columns
- Analyze customer demographics
- Analyze sales by gender
- Analyze sales by age group
- Identify top-performing states
- Analyze purchasing behavior by marital status
- Analyze sales by occupation
- Identify top-performing product categories
- Identify the most frequently ordered products
- Generate useful business insights from the data

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains customer and sales-related information.

Important columns include:

- `User_ID` – Unique customer identifier
- `Cust_name` – Customer name
- `Product_ID` – Product identifier
- `Gender` – Customer gender
- `Age Group` – Customer age category
- `Age` – Customer age
- `Marital_Status` – Marital status
- `State` – Customer state
- `Zone` – Geographic zone
- `Occupation` – Customer occupation
- `Product_Category` – Product category
- `Orders` – Number of orders
- `Amount` – Purchase amount

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Examined the first few records.
3. Checked dataset dimensions.
4. Inspected data types and non-null values.
5. Removed unnecessary columns:
   - `Status`
   - `unnamed1`
6. Checked missing values using `isnull()`.
7. Removed rows containing missing values using `dropna()`.
8. Converted the `Amount` column from float to integer.

### Dataset Size

Initial dataset:

- Rows: 11,251
- Columns: 15

After removing unnecessary columns:

- Rows: 11,251
- Columns: 13

After removing missing values:

- Rows: 11,239
- Columns: 13

---

## 📊 Exploratory Data Analysis

### 1. Gender Analysis

The project analyzes:

- Number of buyers by gender
- Total sales amount by gender

This helps understand purchasing participation and spending patterns across genders.

---

### 2. Age Group Analysis

The project analyzes:

- Number of customers in each age group
- Gender distribution within age groups
- Total sales amount by age group

This helps identify the age groups contributing most to sales.

---

### 3. State Analysis

The project identifies the top 10 states based on:

- Total number of orders
- Total sales amount

The analysis highlights Uttar Pradesh, Maharashtra and Karnataka among the leading states in the analyzed data.

---

### 4. Marital Status Analysis

The project analyzes:

- Number of customers by marital status
- Sales amount by marital status and gender

The analysis indicates strong purchasing activity among married female customers.

---

### 5. Occupation Analysis

Customer occupations are analyzed based on:

- Number of buyers
- Total sales amount

The analysis identifies IT, Healthcare and Aviation among the prominent occupations in the dataset.

---

### 6. Product Category Analysis

The project analyzes:

- Number of orders by product category
- Total sales amount by product category

Food, Clothing and Electronics are highlighted as major product categories in the analysis.

---

### 7. Product-Level Analysis

The project identifies the top 10 products based on total number of orders.

This helps identify products with the highest order volumes.

---

## 📈 Visualizations

The project uses:

- Count plots
- Bar plots
- Grouped bar plots
- Product-level sales visualizations

Libraries used for visualization:

```python


🔍 Key Insights
Based on the analysis:
- Uttar Pradesh, Maharashtra and Karnataka are among the leading states by orders and sales.
- Married female customers show strong purchasing activity.
- Customers in the 26–35 age group are an important segment.
- IT, Healthcare and Aviation are prominent occupations in the analysis.
- Food, Clothing and Electronics are among the major product categories.
- The analysis identifies the top products based on order volume.
💡 Business Recommendations
Based on the observed patterns, businesses can:
- Focus marketing campaigns on high-performing customer segments.
- Develop targeted offers for the 26–35 age group.
- Strengthen marketing in high-performing states.
- Create targeted campaigns for high-value occupations.
- Promote high-performing product categories.
- Use product-level order trends for inventory planning.
- Develop personalized offers based on customer demographics.
🚀 Future Improvements
This project can be extended by:
- Creating an interactive Power BI dashboard
- Performing customer segmentation
- Calculating Customer Lifetime Value
- Performing RFM analysis
- Building sales forecasting models
- Performing correlation analysis
- Applying machine learning for customer purchase prediction
- Creating automated reporting
- Adding interactive filters and dashboards
▶️ How to Run the Project
1. Clone the repository
git clone https://github.com/YOUR-USERNAME/Store-Sales-Data-Analysis.git

2. Navigate to the project
cd Store-Sales-Data-Analysis

3. Install dependencies
pip install -r requirements.txt

4. Start Jupyter Notebook
jupyter notebook

5. Open
Store_Sales_Data.ipynb

Make sure store_data.csv is located in the same directory as the notebook.
📦 Requirements
The project requires:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
👨‍💻 Author
Arjun Thakur
Data Analytics | Python | SQL | Power BI | Excel
⭐ If you found this project useful
Feel free to ⭐ star the repository and explore the analysis.

---

# 6. requirements.txt

Create:

```text
requirements.txt

Put:
numpy
pandas
matplotlib
seaborn
jupyter

This makes your project look much more professional.
7. .gitignore
Create:
.gitignore

Put:
# Python
__pycache__/
*.py[cod]
*$py.class

# Jupyter
.ipynb_checkpoints/

# Virtual environment
venv/
env/
.venv/

# IDE
.vscode/
.idea/

# OS
.DS_Store
Thumbs.db

# Python cache
.pytest_cache/

# Secrets
.env
*.env

A .gitignore tells Git which files should not be committed; GitHub recommends using one for files you don't want checked into the repository. GitHub Docs
8. Your project workflow
Your notebook's workflow is actually quite good for a beginner/intermediate data-analysis portfolio project:
Raw Dataset
     ↓
Load Dataset
     ↓
Initial Exploration
     ↓
Shape & Data Types
     ↓
Remove Unnecessary Columns
     ↓
Check Missing Values
     ↓
Remove Missing Records
     ↓
Data Type Conversion
     ↓
Descriptive Statistics
     ↓
Exploratory Data Analysis
     ↓
Customer Analysis
     ↓
State Analysis
     ↓
Occupation Analysis
     ↓
Product Analysis
     ↓
Business Insights
     ↓
Conclusion
import matplotlib.pyplot as plt
import seaborn as sns

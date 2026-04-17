# 🍽️ EazyDiner Data Analysis Project

## 📌 Project Overview  
This project focuses on **web scraping restaurant data from EazyDiner** and performing **data cleaning, transformation, and exploratory data analysis (EDA)** to extract meaningful insights.  
The goal is to understand **restaurant pricing, ratings, cuisine distribution, and city-wise trends**.

## ⚙️ Workflow  

### 1. Web Scraping  
- Extracted restaurant data from EazyDiner website  
- Saved raw data as `Eazy_Diner.csv`  

### 2. Data Cleaning & Preprocessing  
- Handled missing values and duplicates  
- Converted cost into numeric format  
- Standardized text columns (City, Cuisine, etc.)  
- Treated outliers using IQR method  
- Saved cleaned data as `Eazy_Diner_Cleaned.csv`  

### 3. Exploratory Data Analysis (EDA)  
- Univariate Analysis (Cost, Ratings)  
- Bivariate Analysis (Cost vs Ratings, City vs Cost, etc.)  
- Categorical Analysis (Cuisine & City distribution)  

### 4. Data Visualization  
- Histogram & KDE plots  
- Box plots & Violin plots  
- Scatter plots & Line plots  
- Count plots & Bar charts  
- Heatmap & Pair plot  

## 📊 Key Insights  

- Most restaurants fall in the **mid-price range (₹500–₹2000)**  
- Ratings are generally high (**4.0–4.5**) across cities  
- **Multicuisine and Indian cuisines dominate** the platform  
- Metro cities like **Bengaluru, Delhi-NCR, and Mumbai** have the highest restaurant count  
- There is **no strong correlation between cost and ratings**  

## 🛠️ Technologies Used  

- Python 🐍  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- BeautifulSoup (for web scraping)  

## 📁 Project Structure  
- eazy_diner.csv # Raw scraped data
- eazy_diner_Cleaned.csv # Cleaned dataset
- EDA_Notebook.ipynb # Jupyter Notebook with analysis
- README.md # Project documentation

## 🎯 Conclusion  

This project demonstrates how **web scraping and data analysis** can be used to gain insights into real-world datasets.  
It highlights trends in **customer preferences, pricing patterns, and restaurant distribution**.


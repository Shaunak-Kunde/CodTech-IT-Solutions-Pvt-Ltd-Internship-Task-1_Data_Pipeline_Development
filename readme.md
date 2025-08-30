# CODTECH Internship – Task 1: Data Pipeline Development  

This project is part of my **CODTECH Virtual Internship** under **Data Science**.  
The goal is to build a **data pipeline** for ETL (Extract, Transform, Load) and perform **exploratory data analysis (EDA)** on the BigBasket dataset.  

---

## 🚀 Project Workflow

1. **Data Loading**  
   - Load dataset (`BigBasket Products.csv`) using Pandas.  
   
2. **Preprocessing & Cleaning**  
   - Handle missing values.  
   - Remove duplicates.  
   - Convert data types (e.g., `sale_price`, `discount_pct`).  

3. **Feature Engineering**  
   - Extract useful features like `discount_pct`.  
   - Encode categorical variables (Brand, Category, etc.) for ML compatibility.  

4. **Transformation & Scaling**  
   - Standardize numerical columns using `StandardScaler`.  

5. **Visualization (EDA)**  
   - Distribution of numerical features.  
   - Top 10 brands/products/categories analysis.  
   - Discounts vs Products.  
   - Scatter plot between `sale_price` and `rating`.  
   - Pie charts for category distribution.  

6. **Export Processed Data**  
   - Save cleaned dataset as `BigBasket_Processed.csv`.  
   - For GitHub, only a **sampled dataset** is uploaded due to large size.  

---

## 📊 Visualizations

- Top 10 categories by product count (pie chart)  
- Top 10 products offering highest discount (%)  
- Bottom 10 products by sale price  
- Top 50 brands by average ratings  
- Scatter plot of Sale Price vs Rating  

---

## 🛠️ Tools & Libraries

- **Python 3.10+**  
- **Pandas** – Data handling  
- **NumPy** – Numerical operations  
- **Scikit-learn** – Preprocessing & Scaling  
- **Matplotlib** – Visualization  
- **Seaborn** – Visualization  

---

## 📂 Project Structure
Task-1 Data Pipeline Development/
│── BigBasket Products.csv # Original dataset (not uploaded to GitHub due to size)
│── BigBasket_Processed.csv # Processed dataset (saved locally, sampled for GitHub)
│── Task1_Data_Pipeline.ipynb # Main Jupyter Notebook
│── requirements.txt # Required Python libraries
│── README.md # Project documentation


## 📊 Summary & Insights

- The **BigBasket dataset** contains multiple categories and brands with varying discounts.  
- **Data Cleaning & Preprocessing** handled missing values, standardized formats, and removed duplicates.  
- **Feature Engineering** created new columns such as:
  - `discount` (absolute difference between market & sale price)  
  - `discount_pct` (percentage discount)  
  - `description_length` (word count of product description)  
- **Transformation** included one-hot encoding for categorical features and scaling of numerical features.  
- **EDA Findings**:
  - Top brands like **Fresho** and **bb Royal** dominate product counts.  
  - Some categories consistently provide higher discounts, giving insights into pricing strategies.  

### ✅ Deliverables
- Clean dataset → `bigbasket_processed.csv`  
- Reusable sklearn pipeline → `bigbasket_pipeline.pkl`  
- Visualizations of brand distribution & discounts  
- Full pipeline automation in this notebook  

## ⚠️ Note  

- The **original dataset** is very large (~300MB), so only **sample data** is committed to GitHub.  
- Run the notebook locally with the full dataset for complete results.  


This concludes **Task-1: Data Pipeline Development** for the CodTech Internship 🚀

---

👨‍💻 Developed by: **Shaunak Damodar Sinai Kunde**  
# CODTECH Internship – Task 1: Data Pipeline Development  

### Company:- CodTech IT Solutions Pvt. Ltd., Hyderabad
### Name:- Shaunak Damodar Sinai Kunde
### Intern ID:- CT04DY1729
### Domain:- Data Science
### Duration:- 4 weeks
### Mentor:- Muzammil Ahmed

This project is part of my **CODTECH Virtual Internship** under **Data Science**.  
The goal is to build a **data pipeline** for ETL (Extract, Transform, Load) and perform **exploratory data analysis (EDA)** on the BigBasket dataset.  

---

## 🚀 Project Workflow

1. **Data Loading**  
   - Load dataset from Kaggle Link https://www.kaggle.com/code/ridamahmood005/indian-grocery-supermarket-big-basket-eda
   - (`BigBasket Products.csv`) using Pandas.  
   
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
│── BigBasket Products.csv # Original dataset
│── BigBasket_Processed.csv.parquet # Processed dataset (saved locally, sampled for GitHub)
│── bigbasket_pipeline.ipynb # Main Jupyter Notebook
│── requirements.txt # Required Python libraries
│── requirements.txt
│── label_encoders.pkl
│── readme.md # Project documentation
│── scaler.pkl




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
- <img width="326" height="539" alt="t1 1" src="https://github.com/user-attachments/assets/b260af81-7cba-4c7e-89ec-e475dd6d922d" />

- Full pipeline automation in this notebook  

## ⚠️ Note  

- The **processed dataset** is very large (~309MB), so only **sample data** is committed to GitHub.  
- Run the notebook locally with the full dataset for complete results.  

This concludes **Task-1: Data Pipeline Development** for the CodTech Internship 🚀

👨‍💻 Developed by: **Shaunak Damodar Sinai Kunde**  




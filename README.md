#  Data Analyst Internship - Task 1: Data Cleaning & Preprocessing

##  Objective

To clean and preprocess the `Mall_Customers.csv` dataset by handling missing values, removing duplicates, standardizing text, fixing data types, and generating initial visual insights.

---

## Dataset

- **Name:** Mall Customer Segmentation Data  
- **Source:** Kaggle ([Link](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python))  
- **Shape:** 200 rows × 5 columns (original)

---

## 🛠️ Steps Performed

 Step                        -             Description       
 Missing Value Check        - Used `.isnull().sum()` — no missing values found                           
 Duplicate Removal          - Used `.drop_duplicates()` — ensured no repeated records                    
 Text Standardization       - Standardized `Gender` values (e.g., "male", "Male ") → "Male"              
 Column Renaming            - Converted column headers to lowercase + underscores                        
 Data Type Conversion       - Ensured `age` is of type `int`                                             
 Export                     - Saved final cleaned dataset as `Mall_Customers_Cleaned.csv`                

---

##  Visualizations

### 1. Gender Distribution

![Gender Distribution](gender_distribution.png)

> Shows a relatively balanced count of Male vs Female customers.

---

### 2. Age Distribution

![Age Distribution](age_distribution.png)

> Most customers fall between the ages of 30 and 40.

---

### 3. Income vs Spending Score

![Income vs Spending Score](income_vs_spending.png)

> Identifies distinct customer clusters based on income and spending behavior.

---

##  Observations & Insights

- **Balanced Gender Ratio:** The dataset has a near-even split between male and female customers.
- **Major Age Group:** Majority of the customers are young adults (25–40 years).
- **Spending Patterns:** Higher income doesn’t always correlate with high spending; clusters are visible.

---

## ⚠ Anomalies or Issues

- No major anomalies detected.
- Minor inconsistencies in text case and spacing (e.g., " male", "FEMALE ") were standardized.

---

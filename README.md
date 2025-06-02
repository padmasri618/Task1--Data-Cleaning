#  Data Analyst Internship - Task 1: Data Cleaning & Preprocessing

##  Objective

To clean and preprocess the `Mall_Customers.csv` dataset by handling missing values, removing duplicates, standardizing text, fixing data types, and generating initial visual insights.

---

## Dataset

- **Name:** Mall Customer Segmentation Data  
- **Source:** Kaggle ([Link](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python))  
- **Shape:** 200 rows × 5 columns (original)

---

##  Steps Performed

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

![image1](https://github.com/user-attachments/assets/bfe3b5bd-cc84-4d75-852b-323789360ff9)


> Shows a relatively balanced count of Male vs Female customers.

---

### 2. Age Distribution
![image2](https://github.com/user-attachments/assets/7192d7f4-b604-4c84-b623-bede19583889)


> Most customers fall between the ages of 30 and 40.

---

### 3. Income vs Spending Score

![image3](https://github.com/user-attachments/assets/df6e7607-93ec-4243-8462-2d2feae6c661)


> Identifies distinct customer clusters based on income and spending behavior.

---

##  Observations & Insights

- **Balanced Gender Ratio:** The dataset has a near-even split between male and female customers.
- **Major Age Group:** Majority of the customers are young adults (25–40 years).
- **Spending Patterns:** Higher income doesn’t always correlate with high spending; clusters are visible.

---

##  Anomalies or Issues

- No major anomalies detected.
- Minor inconsistencies in text case and spacing (e.g., " male", "FEMALE ") were standardized.

---
## Dataset Name: Mall Customer Segmentation Data
- This dataset contains demographic and spending behavior information about customers visiting a mall. It is often used for clustering and segmentation analysis to identify different types of shoppers.
---
## Project Content
- File / Folder Name	Description
- Mall_Customers.csv -- 	Original raw dataset downloaded from Kaggle
- Mall_Customers_Cleaned.csv	--Final cleaned dataset after preprocessing
- data_cleaning.py	-- Python script performing all data cleaning steps
- README.md --	Project documentation with methods, insights, visualizations
---

## Summary of Key Actions
1. Loaded dataset and explored shape, nulls, and types.
2. Cleaned and standardized data (removed duplicates, fixed text, corrected types).

3. Generated essential visualizations.
4. Extracted insights and documented anomalies.
5. Answered related interview-style questions for practice.

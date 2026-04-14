#  Customer Segmentation and Spending Analysis

##  Project Overview

This project analyzes customer behavior using demographic and financial data to identify distinct spending patterns and customer segments. By exploring relationships between income, age, profession, and spending score, the analysis uncovers actionable insights that can support targeted marketing strategies and improve customer engagement.

The project follows a structured data analysis workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, and customer segmentation.

---

##  Objectives

* Understand customer demographics and spending behavior
* Identify relationships between income, age, and spending score
* Segment customers into meaningful business groups
* Provide actionable insights for marketing and business strategy

---

## Dataset

The dataset contains **2000 customer records** with the following features:

* **Customer ID** – Unique identifier
* **Gender** – Male / Female
* **Age** – Customer age
* **Annual Income ($)** – Income level
* **Spending Score (1–100)** – Customer spending behavior
* **Profession** – Occupation category
* **Work Experience** – Years of experience
* **Family Size** – Number of family members

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Data Analysis Process

### 1. Data Cleaning

* Checked for missing values
* Removed duplicate records
* Ensured correct data types

### 2. Feature Engineering

* Created **Income Categories** (Low, Medium, High, Very High)
* Created **Spending Categories** (Low, Medium, High)

### 3. Exploratory Data Analysis (EDA)

* Distribution analysis (Age, Income, Spending Score)
* Relationship analysis (Income vs Spending, Age vs Spending)
* Group comparisons (Profession, Gender)

### 4. Customer Segmentation

Customers were segmented into four groups:

* **High Value** → High income, high spending
* **Rich but Low Spending** → High income, low spending
* **Budget High Spenders** → Low income, high spending
* **Average** → Moderate income and spending

---

## Key Insights

* There is **no strong linear relationship** between income and spending
* High-income customers do not always spend more
* Younger customers tend to show slightly higher spending behavior
* Certain professions (e.g., entertainment, artists) have higher average spending
* The largest segment is **Average customers**, followed by **high-income low spenders**

---

##  Business Recommendations

* Target **high-income low-spending customers** with personalized marketing campaigns
* Retain **high-value customers** through loyalty programs and premium services
* Use behavioral segmentation instead of relying only on demographics
* Develop tailored strategies for different customer segments

---

##  Sample Visualizations

* Age vs Spending Score
* Income vs Spending Score (by Gender)
* Spending by Profession
* Customer Segmentation Distribution

---

##  Future Improvements

* Apply **K-Means Clustering** for data-driven segmentation
* Build a **predictive model** for customer spending
* Create an **interactive dashboard (Power BI / Tableau)**
* Incorporate additional behavioral features

---

##  Conclusion

This project demonstrates how data analysis can be used to better understand customer behavior and support business decision-making. By identifying key customer segments and patterns, businesses can design more effective marketing strategies and improve overall customer satisfaction.

---

##  Author

**Fatih Özhasar**
Data Analyst | Data Science Enthusiast

---

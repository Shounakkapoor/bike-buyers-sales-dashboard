# Bike Buyers Analysis

This repository contains an Excel workbook with a raw dataset and an interactive dashboard that explores which factors influence a customer’s decision to purchase a bike.

---

## 📂 Files

- **Excel Project Dataset.xlsx**  
  - **`bike_buyers`** – Raw customer data: demographics, income, commute distance, region, and purchase flag.  
  - **`Working sheet`** – Cleaned data with an added **Age Bracket** column (Young Adult, Middle Age, Senior).  
  - **`pivot table`** – Pivot tables and pivot charts summarizing:  
    - **Average Income Per Purchase** by Gender & Purchase Decision  
    - **Count of Purchased Bike** by Commute Distance  
    - **Count of Purchased Bike** by Age Bracket  
  - **`Dashboard`** – **Bikes Sales Dashboard** combining the three pivot charts and slicers for:  
    - Marital Status (Married, Single)  
    - Region (Europe, North America, Pacific)  
    - Education (High School, Partial College, etc.)   

---

## 📊 Dataset Overview (`bike_buyers`)

| Column              | Description                                    |
|---------------------|------------------------------------------------|
| **ID**              | Unique customer identifier                     |
| **Marital Status**  | Married (M) or Single (S)                      |
| **Gender**          | Female or Male                                 |
| **Income**          | Annual income (USD)                            |
| **Children**        | Number of children                             |
| **Education**       | Highest education level (e.g. Bachelors)       |
| **Occupation**      | Job category (e.g. Professional, Clerical)     |
| **Home Owner**      | Yes / No                                       |
| **Cars**            | Number of cars owned                           |
| **Commute Distance**| Category (0–1 Miles, 1–2 Miles, 2–5 Miles, etc.)|
| **Region**          | Europe, North America, Pacific                 |
| **Age**             | Age in years                                   |
| **Age Bracket**     | Young Adult / Middle Age / Senior              |
| **Purchased Bike**  | Yes / No                                       |

---

## 🎯 Analysis & Objectives

1. **Pivot Table Summary (`pivot table` sheet)**  
   - **Average Income Per Purchase**  
     Bar chart comparing average income of buyers vs. non-buyers, broken out by gender.  
     _Objective:_ See how income varies between those who purchase bikes and those who don’t.  
   - **Customer Commute**  
     Line chart showing counts of buyers vs. non-buyers by commute distance.  
     _Objective:_ Understand whether shorter or longer commutes correlate with bike purchases.  
   - **Customer Age Bracket**  
     Line chart showing counts of buyers vs. non-buyers across age groups.  
     _Objective:_ Identify which age brackets are most likely to buy a bike.

2. **Bikes Sales Dashboard**  
   Interactive dashboard that brings together the three charts above, with slicers for Marital Status, Region, Education.  
   _Objective:_ Allow real-time filtering to explore how different demographics affect bike-buying behavior.

![Alt Text](https://github.com/Shounakkapoor/bike-buyers-sales-dashboard/blob/main/Bikes%20Sales%20Dashboard.png)
---

## 🚀 How to Use 

1. **Clone or download** this repository.  
2. **Open** `bike_sales_project.xlsx` in Microsoft Excel (or a compatible program).  
3. **Inspect** the **`bike_buyers`** sheet for the raw data.  
4. **See** the **`Working sheet`** to understand how the data was cleaned and categorized.  
5. **Explore** the **`pivot table`** sheet for summary tables and charts.  
6. **Interact** with the **Bikes Sales Dashboard** —use the slicers to filter and watch the charts update instantly.

---

Feel free to copy-paste this into your `README.md`. Let me know if you’d like any tweaks or additional details! 

## Author
**Shounak Kapoor**

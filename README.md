# 📊 Data Professionals Survey Dashboard

This project is a Power BI dashboard that visualizes and analyzes responses from a global survey of data professionals. It highlights key insights like salary trends, job roles, programming language preferences, and work-life satisfaction.

## 🧠 Objective

To provide clear insights into the demographics, satisfaction levels, salaries, and preferences of data professionals using interactive visuals in Power BI.

---

## 📌 Key Insights

- **Top Job Roles:** Data Scientist, Data Engineer, Data Architect and Data Analyst
- **Top Language:** Python is by far the most popular language across all roles
- **Work-Life Balance:** Average rating of **5.74/10**
- **Salary Satisfaction:** Average rating of **4.27/10**
- **Most Respondents:** From the **United States**
- **Breaking into Data:** 42.7% rated it as "Neither easy nor difficult"

---

## ⚙️ Data Cleaning & Preprocessing
Performed using Power BI Query Editor:

- Removed responses where the answer was "Others" for the following questions:

    - Job Role

    - Country

    - Department

    - Favorite Programming Language

Rationale: These generic answers did not add analytical value and were excluded to improve clarity and consistency in visualizations.

- Calculated average yearly salary from reported salary ranges

- Removed duplicate entries and rows with null/empty values

---

## 🧰 Tools Used

- **Power BI Desktop**
- **Power Query (M Language)**
- **DAX for Calculations**
- **Custom Visuals & Filters**

---

## 🖼️ Dashboard Preview
![Data Professionals Survey Dashboard](https://github.com/user-attachments/assets/bea27d25-f7cf-4cdc-a895-05776ac87cd1)


---

## 📁 Files in this Repo

| File | Description |
|------|-------------|
| `data_professionals_survey_raw_dataset.xlsx` | Raw Dataset used for visualization |
| `Data Professionals Survey Dashboard.pbix` | Power BI report file |
| `Data Professionals Survey Dashboard.png` | Final dashboard screenshot |
| `README.md` | This documentation |

---

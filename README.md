# Gretta_Mucyo_FinalExamBigData
# 📊 Student Academic Performance Analysis

This project analyzes students’ academic performance using data analytics techniques in Python and Power BI. It explores the impact of various factors such as gender, study time, failures, absences, and internet access on students' average grades.

## 📁 Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Power BI Dashboard](#power-bi-dashboard)
- [Key Insights](#key-insights)
- [How to Run the Project](#how-to-run-the-project)
- [Screenshots](#screenshots)
- [Conclusion](#conclusion)
- [Author](#author)

---

## 📌 Project Overview

This project was conducted as part of the **INSY 8413 – Introduction to Big Data Analytics** course. The goal was to gain actionable insights into student performance by analyzing educational data using Power BI, with preprocessing done in Python.

---

## 🎯 Objectives

- Understand how different factors affect student performance.
- Visualize data through interactive dashboards.
- Recommend actionable decisions to improve education outcomes.

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib)
- **Power BI Desktop**
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📊 Dataset Description

- The dataset was collected from a real educational institution (not from Kaggle).
- It includes features such as:
  - `sex`, `school`, `studytime`, `failures`, `absences`, `internet`, `G1`, `G2`, `G3`
- A new column `average_grade` was created from the average of G1, G2, and G3.

---

## 🧹 Data Preprocessing

- Removed irrelevant columns
- Converted categorical variables into readable formats
- Created derived columns such as `average_grade`
- Saved the cleaned file as `cleaned_student_data.csv` for Power BI

---

## 📈 Power BI Dashboard

The dashboard includes the following interactive visuals:

1. **Gender Distribution** – Pie Chart  
2. **Average Grade Distribution** – Histogram  
3. **Study Time vs Average Grade** – Scatter Plot  
4. **Failures vs Absences** – Box Plot  
5. **Internet Access vs Performance** – Stacked Bar  
6. **Filters** – For gender, study time, failures, internet access, school

---

## 🔍 Key Insights

- Students with more study time tend to perform better.
- Internet access positively correlates with academic performance.
- A higher number of past failures is associated with more absences.
- Female students had a slightly higher average grade.

---



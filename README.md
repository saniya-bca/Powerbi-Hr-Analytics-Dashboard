# Powerbi-Hr-Analytics-Dashboard


## 📌 Project Overview

This project focuses on analyzing employee attrition using an interactive dashboard built in Power BI. The goal is to identify key factors contributing to employee turnover and provide actionable insights to improve employee retention.

---

## 🎯 Objectives

* Analyze overall employee attrition
* Identify trends based on age, salary, job role, and education
* Understand factors influencing employee turnover
* Provide data-driven insights for HR decision-making

---

## 📁 Dataset Information

The dataset includes employee-related information such as:

* Employee ID
* Age
* Gender
* Education Field
* Job Role
* Salary
* Years at Company
* Attrition (Yes/No)

---

## ⚙️ Tools & Technologies Used

* Power BI
* Power Query (Data Cleaning & Transformation)
* DAX (Data Analysis Expressions)

---

## 🧮 Key Calculations

### ✔ Attrition Count (Calculated Column)

AttritionCount = IF(Attrition = "Yes", 1, 0)

### ✔ Attrition Rate (DAX Measure)

Attrition Rate = SUM(AttritionCount) / COUNT(EmployeeID)

---

## 📊 Dashboard Features

* KPI Cards:

  * Total Employees
  * Total Attrition
  * Attrition Rate
  * Average Age
  * Average Salary
  * Average Years at Company

* Visualizations:

  * Attrition by Age Group
  * Attrition by Gender
  * Attrition by Education Field
  * Attrition by Salary Slab
  * Attrition by Job Role
  * Attrition by Years at Company

---

## 🔍 Key Insights

* Highest attrition observed in age group 26–35
* Employees with lower salary (≤5K) show higher attrition
* Laboratory Technicians and Sales Executives have higher turnover
* Most employees leave within the first few years
* Male employees have slightly higher attrition

---

## 💡 Business Recommendations

* Improve salary structure for low-income employees
* Focus on employee engagement in early career stages
* Provide growth opportunities and promotions
* Address high attrition roles with targeted strategies

---

## 📸 Dashboard Preview

(Add your screenshot here)

Example:
![Dashboard Screenshot](your-image-link-here)

---

## 🚀 Conclusion

This dashboard helps HR teams understand employee behavior and take proactive steps to reduce attrition. It enables data-driven decision-making and improves workforce management.

---

## 👩‍💻 Author

**Saniya Shaikh**


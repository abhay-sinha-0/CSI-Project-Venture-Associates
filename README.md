# 📊 Venture Associates INC – KPI Performance Dashboard in Power BI

## 🔍 Project Overview

This Power BI project is built for **Venture Associates INC**, a manufacturing startup managing five core products: **Alpha, Beta, Gamma, Delta, and Theta**. The goal is to transform their manual KPI tracking into an interactive, cloud-powered business intelligence solution using **Power BI Desktop**.

The report provides **dynamic performance monitoring**, **trend analysis**, and **KPI evaluation** across time, products, and product heads using advanced visuals, DAX measures, conditional formatting, and slicers.

---

## 🚀 Key Features

- **Interactive KPI Trend Matrix**  
  Tabular view of all 5 KPIs (CPT, LVT, NKT, MGT, IDT) across 5 months, with color-coded status (Red/Amber/Green) based on thresholds.

- **Dynamic Line Chart with Thresholds**  
  Line chart showing selected KPI trends over time with dynamically updating **HT** and **LT** reference lines using measures.

- **Conditional Line Coloring**  
  Line changes color based on performance zone:
  - Green: Above HT
  - Amber: Between HT and LT
  - Red: Below LT

- **Product Head & Product Slicers**  
  Filters ensure users see only relevant data tied to their role.

- **Performance Status Summary**  
  Donut charts, status cards, and bar charts showing Poor/Average/Good classification by product or month.

- **Animated Scatter Plot (MGT vs CPT)**  
  Interactive scatter plot showing KPI relationships over time using play axis for month-wise animation.

- **Decomposition Tree**  
  Visual drill-down by Product → KPI → Status → Month.

- **Forecasting** *(optional)*  
  Trend prediction using built-in Power BI analytics for selected KPIs.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query (M Language)**
- **DAX (Data Analysis Expressions)**
- **Excel (data source)**

---

## 📁 File Structure

📦Venture-KPI-PowerBI
┣ 📊 Venture Associates Dashboard.pbix
┣ 📈 Screenshots/
┣ 📑 README.md
┗ 📂 Data/
┗ 📄 Venture Associates Data.xlsx



---

## 🧠 KPI Evaluation Logic

Each KPI is evaluated based on thresholds:

| Status  | Condition                                | Color  |
|---------|-------------------------------------------|--------|
| Poor    | `Actual Value ≤ LT`                      | 🔴 Red  |
| Average | `LT < Actual Value < HT`                 | 🟡 Amber|
| Good    | `Actual Value ≥ HT`                      | 🟢 Green|

---

## 📌 How to Use

1. Open `Venture Associates Dashboard.pbix` in Power BI Desktop.
2. Review the main dashboard pages:
   - **Overview**
   - **KPI Matrix**
   - **Trend Analysis**
   - **Scatter Comparison**
   - **Details Table**
3. Use the slicers (Product, Head, KPI) to filter views.
4. Hover over visuals or play animations to explore insights.

---


## 🤝 Acknowledgments

This dashboard was developed as a performance and business monitoring solution for Venture Associates INC, designed to bridge manual KPI tracking with modern BI capabilities.

---

## 📬 Contact

**Developer**: Abhay Kumar  
**Email**: [abhaykumar1522003abk@gmail.com]  
**LinkedIn**: [linkedin.com/in/abhaykumar](https://www.linkedin.com/in/abhay-kumar01/)

---


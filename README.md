# Product Count Analysis – VEDA Technology Task 15

## 📌 Project Overview

This project is completed as part of the VEDA Technology Data Analytics Internship – Level 1, Day 15.

The objective of this task is to analyze product counts by category using Microsoft Excel and identify the category with the highest product count.

## 🎯 Objectives

* Count products by category.
* Identify the category with the highest count.
* Check unique products.
* Present the analysis using a table and bar chart.

## 🛠️ Tools Used

* Microsoft Excel
* COUNTIF Formula
* MAX Formula
* INDEX and MATCH Functions
* Bar Chart

## 📊 Analysis Performed

The following categories were analyzed:

* Furniture
* Office Supplies
* Technology

### Excel Formulas Used

**Category-wise Count:**

```excel
=COUNTIF('Raw Data'!C:C,A2)
```

**Highest Count:**

```excel
=MAX(B2:B4)
```

**Largest Category:**

```excel
=INDEX(A2:A4,MATCH(MAX(B2:B4),B2:B4,0))
```

## 📈 Results

| Category        | Product Count |
| --------------- | ------------: |
| Furniture       |            31 |
| Office Supplies |            39 |
| Technology      |            30 |

**Largest Category:** Office Supplies

**Highest Product Count:** 39

## 📂 Project Files

* `Product_Count_Analysis_Presentable.xlsx` – Excel analysis file.
* `README.md` – Project documentation.

## ✅ Conclusion

The product count analysis was performed using Excel COUNTIF and other formulas. Office Supplies recorded the highest product count among the analyzed categories.

## 👩‍💻 Author

Bhagya

Data Analytics Intern – VEDA Technology

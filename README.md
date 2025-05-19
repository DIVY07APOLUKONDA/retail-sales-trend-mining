
# 📦 E-Commerce Sales Analytics with Python

In this project, we analyze the 2019 sales data from Kmart, one of the leading online retailers in the U.S., to uncover trends that can shape their 2020 sales strategy. The analysis explores product performance, purchasing behavior, time-based trends, and customer locations.

---

## 💼 Project Context

Kmart’s leadership team required a detailed analysis of the previous year’s transactions to guide their sales optimization efforts in the upcoming year. This project aims to answer pivotal questions related to:

- Peak sales months
- High-performing cities
- Ideal times for running ads
- Most popular and frequently bundled products

---

## 📊 Business Questions Answered

1. In which month did the company generate the highest revenue?
2. Which locations reported the most purchases?
3. At what time of day do customers shop the most?
4. What product was sold in the highest quantity and why?
5. Which products tend to be bought together?

---

## 📂 Dataset Summary

- **Company**: Kmart  
- **Duration**: January 2019 – December 2019  
- **Cities Covered**: 9  
- **Orders Recorded**: 178,437  
- **Unique Items Sold**: 19  
- **Key Metrics**: Sales Volume, Total Revenue, Product Bundling  

---

## 🧠 Analysis Approach (Python)

1. Combined monthly CSV files into one complete dataset using Pandas  
2. Handled null entries and inconsistent values during preprocessing  
3. Filtered and formatted data for time-based and categorical analysis  
4. Built multiple visualizations using Matplotlib and Seaborn  
5. Extracted actionable insights for each business question  

---

## 📅 Monthly Sales Performance

- Grouped records by order date to calculate monthly revenue  
- Created bar plots to visualize the spike in sales over the months  
- December emerged as the highest-grossing month

---

## 🌍 Top-Selling Locations

- Parsed customer shipping addresses to extract city names  
- Grouped and visualized total purchases by city  
- San Francisco had the largest order volume

---

## 🕒 Optimal Advertising Times

- Extracted hour data from the purchase timestamps  
- Plotted hourly order frequencies to identify prime ad slots  
- Purchase peaks occurred just before 12 PM and around 7 PM

---

## 🏆 Best-Selling Items

- Grouped products by quantity sold  
- Bar charts showed the top items by volume  
- Found a clear inverse relationship between price and units sold

---

## 🤝 Product Bundling Insights

- Analyzed repeated Order IDs to find grouped items  
- Merged products in a single purchase to identify common combos  
- Listed the most frequent product bundles

---

## 🧰 Tools & Libraries

![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23#ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

- **Pandas**: Data wrangling and manipulation  
- **Matplotlib/Seaborn/Plotly**: Data visualization and trend representation  
- **Jupyter Notebook**: Environment for developing and documenting analysis

---

## 📌 Summary of Insights

- December brought in the highest revenue (~$9.22 million)  
- San Francisco stood out as the city with the most purchases  
- Midday and early evening are optimal for ad placement  
- Affordable items like `'AAA Batteries (4-pack)'` dominate sales  
- Frequently bundled products reveal customer preferences for cross-selling

# **Sales Dashboard**

## **Description**

The Sales Dashboard is designed to provide an insightful comparison of Year-to-Date (YTD) versus Previous Year-to-Date (PYTD) performance across Sales, Quantity, and Gross Profit. The results are grouped by various time frames, including Quarters and Months, and further segmented by Item Categories. Additionally, the dashboard displays Gross Profit Percentage (GP%) to enhance the analysis.

### **Key Features:**
- **Slicers:**  
  - **Years:** Allows users to filter data by specific years.
  - **Values:** Filters can be applied based on Sales, Quantity, and Gross Profit.

- **Interactive Visualizations:**  
  The visualizations can be dynamically filtered by clicking on charts segmented by Months and Categories.

### **Visualizations:**

1. **YTD vs PYTD by Category (Treemap):**  
   A treemap that showcases item categories along with their variances. This visualization provides a clear overview of the performance of different categories.
   
   ![Treemap Visualization](https://github.com/DrodBR/SalesDashboard/blob/main/Visualisation1.png)

2. **YTD vs PYTD by Month (Waterfall Chart):**  
   A waterfall chart that allows users to drill down from quarters to months and further into categories. This visualization effectively demonstrates the changes in values over time.
   
   ![Waterfall Visualization](https://github.com/DrodBR/SalesDashboard/blob/main/Visualisation2.png)

3. **KPI Cards:**  
   Cards displaying critical metrics, including YTD, PYTD, YTD vs. PYTD, Gross Profit in absolute values (GP$), and Gross Profit as a percentage (GP%).
   
   ![KPI Cards Visualization](https://github.com/DrodBR/SalesDashboard/blob/main/Visualisation3.png)

4. **Line and Stacked Column Chart (YTD vs PYTD):**  
   A combined line and stacked column chart that can be drilled down from quarters to months. The columns represent the contribution of each category to the overall totals, with a line indicating the PYTD results.
   
   ![Line and Stacked Column Visualization](https://github.com/DrodBR/SalesDashboard/blob/main/Visualisation4.png)

5. **Scatter Chart (Values and GP% by Item and Category):**  
   This scatter chart is used to identify how individual items and categories are performing based on their values and GP%.
   
   ![Scatter Chart Visualization](https://github.com/DrodBR/SalesDashboard/blob/main/Visualisation5.png)

### **Dataset Information:**

This dashboard is built using a dataset of vegetable sales from a supermarket, covering the period from **July 1, 2020, to June 30, 2023**. The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/yapwh1208/supermarket-sales-data).

## **Usage**

The dashboard can be used to analyze the performance of sales over time, compare current and previous periods, and identify trends or outliers in specific categories or items.

## **License**

This project is licensed under the MIT License. See the LICENSE file for more details.

#  Sales Data Analysis & Forecasting Project

##  Project Overview

This project focuses on analyzing historical sales data to identify trends, patterns, and key business insights. It also includes forecasting future sales using analytical techniques.

The analysis is performed using **Python, Excel, SQL, and Power BI**, providing both technical insights and interactive dashboards.

---

##  Objectives

* Analyze sales trends over time
* Identify seasonal patterns in sales
* Perform region-wise sales analysis
* Forecast future sales for better decision-making
* Build interactive dashboards for visualization

---

##  Tools & Technologies

* **Python** 
* **Excel** (Pivot Tables, Charts)
* **SQL** (Data querying and transformation)
* **Power BI** (Dashboard & Visualization)

---

##  Dataset

* The dataset contains sales transaction details such as:

  * Order Date
  * Sales Amount
  * Region
  * Product Details

---

##  Key Analysis Performed

### 1. Data Cleaning

* Removed null values
* Standardized date formats
* Created Month-Year columns for trend analysis

### 2. Exploratory Data Analysis (EDA)

* Monthly and yearly sales trends
* Region-wise sales contribution
* Identification of highest and lowest sales periods

### 3. Next 7 Days Sales Forecast

* Sales are low on **31st December**, followed by a **sharp spike on 1st January**, indicating strong New Year demand
* A **gradual decline from 2nd to 5th January** reflects reduced post-holiday activity
* A **significant surge on 6th January** suggests delayed or event-driven purchases
* Overall trend highlights **seasonal and event-driven fluctuations in sales**

### 4. Seasonal Trend Analysis

* Sales decrease from **November to February**
* Gradual increase from **March onwards**
* Peak sales observed in **September**

### 5. Region-wise Analysis

* Maximum sales recorded in **Western region (~31.4%)**

### 6. Forecasting

* Predicted sales for next 7 days using time-series approach
* Example forecast insights:

  * Fluctuating short-term sales trend
  * Sudden spikes indicate demand variability

---

##  Key Insights

* Sales follow a **seasonal pattern**
* Early-year months show **low demand**
* Mid-year growth leads to **peak performance in September**
* Businesses should:

  * Optimize strategies during low-demand periods
  * Maximize marketing during peak months

---

##  Dashboard (Power BI)

* Interactive visualizations including:

  * Sales trend line chart
  * Region-wise pie chart
  * Monthly performance analysis

---

##  How to Run the Project

### Python

1. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Run the analysis script:

   ```bash
   python analysis.py
   ```



---

##  Future Improvements

* Add advanced forecasting models
* Include customer segmentation
* Automate dashboard updates

---

##  Author

**Raj Roshan**

---

## ⭐ Conclusion

Sales show a clear seasonal pattern with early decline and mid-year growth. Businesses can improve performance by planning strategies around demand fluctuations and leveraging peak sales periods effectively.

---

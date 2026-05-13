
---
<p align="center">
  <img src="https://github.com/user-attachments/assets/d007d335-052f-481d-8e10-818c86061478" alt="purchasing-concept">
</p>

Change Icon emoji 🔥🔍📘🚩 to your likings by clicking "Start" + "."

# 📊 Project Title: Purchasing Performance Analysis (Power BI)



---

## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)  
2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)  
3. [🧠 Design Thinking Process](#-design-thinking-process)  
4. [📊 Key Insights & Visualizations](#-key-insights--visualizations)  
5. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

---

## 📌 Background & Overview  

### Objective:
### 📖 What is this project about? 
 
Create an Operations Dashboard that provides leadership with a clear, easy-to-understand view to support better decision-making and operational performance.
- Ensure sufficient inventory for sales
- Delivered on time
- Optimized procurement costs


### 👤 Who is this project for?  

✔️ Data analysts & business analysts  
✔️ Supply chain managers & inventory controllers  
✔️ Decision-makers & stakeholders  

###  ❓Business Questions:  

✔️ Identify high-performing and best-selling products to increase revenue and customer growth.   
✔️ Manage procurement lead time to ensure smooth operations and timely delivery.  
✔️ Optimize purchasing costs to improve company profitability.  


### 🎯Project Outcome:  chua lam`
Summarize key findings and insights/ trends/ themes in a concise, bullet-point 
format.  

 _Example:_

✔️ Sales Trends: The top X% of products generate Y% of revenue.  
✔️ Inventory Optimization: Certain products are frequently out-of-stock, causing revenue loss.  
✔️ Customer Behavior: Returning customers spend Z% more per transaction than new customers.  

---

## 📂 Dataset Description & Data Structure  

### 📌 Data Source  
- Source:  AdventureWorks 2019 from BigQuery
- Format: .csv

### 📊 Data Structure & Relationships  

#### 1️⃣ Tables Used:  
There are 7 tables in the dataset.  

#### 2️⃣ Table Schema & Data Snapshot  

Table 1: Product  
<img width="1829" height="798" alt="image" src="https://github.com/user-attachments/assets/2f1ed83d-f069-4334-ad22-c67050af060b" />

Table 2: ProductTable
<img width="1226" height="794" alt="image" src="https://github.com/user-attachments/assets/54ff2812-6e59-45dd-91cd-762fe7cc03a9" />

Table 3: OrderDetail
<img width="1828" height="772" alt="image" src="https://github.com/user-attachments/assets/3098a499-391b-4d69-af73-11dd0408dc1e" />

Table 4: OrderHeader
<img width="1607" height="767" alt="image" src="https://github.com/user-attachments/assets/0701bb79-30fe-456d-9600-2a869f900dbc" />

Table 5: ProductVendor
<img width="1611" height="770" alt="image" src="https://github.com/user-attachments/assets/4e787681-77d2-431a-8495-874efca9fbd7" />

Table 6: Vendor
<img width="1608" height="773" alt="image" src="https://github.com/user-attachments/assets/6e3aa597-3684-4d3e-a80c-9bb5dd21f01f" />

Table 7: ShipMethod
<img width="1279" height="332" alt="image" src="https://github.com/user-attachments/assets/eb0c3d33-4969-49f9-a577-ba86dfce2278" />


#### 3️⃣ Data Relationships:  
<img width="1190" height="719" alt="image" src="https://github.com/user-attachments/assets/c9fa855a-d178-48bb-85e2-4859b3571f38" />


---

## 🧠 Design Thinking Process  

1️⃣ Empathize  
The Empathize stage focuses on understanding users’ pain points, needs, and business challenges. Through research and observation, we gain insights into what users truly need in order to build effective and user-centered solutions.
<img width="1706" height="393" alt="image" src="https://github.com/user-attachments/assets/897c6e17-a618-47e2-a11c-63f8c8eae26a" />

2️⃣ Define point of view  
The Define stage focuses on clearly identifying the core business problem and key objectives based on user needs and insights gathered from the Empathize stage.
<img width="1680" height="541" alt="image" src="https://github.com/user-attachments/assets/f664ed68-cf1c-46ce-96ca-c4b4aa256979" />

3️⃣ Ideate  
The Ideate stage focuses on generating ideas, metrics, and analytical approaches to solve the defined business problem effectively.
<img width="1743" height="610" alt="image" src="https://github.com/user-attachments/assets/41662819-d618-4d9a-b08b-ae743d4fa8ed" />

4️⃣ Prototype and Review  
The Prototype & Review stage focuses on designing, testing, and refining dashboard layouts and visuals to ensure the solution is clear, interactive, and supports effective decision-making.

---

## ⚒️ Main Process

1️⃣ Data Cleaning & Preprocessing  
1. Connect to database: I directly connect AdventureWorks 2019 database from google BigQuery to PowerBI and select tables related to Purchasing.
<img width="1105" height="881" alt="image" src="https://github.com/user-attachments/assets/937d1f29-5ba2-4a14-9c09-06ddc475be74" />

2. Process raw data such as removing duplicates, outliers, missing values, standardize values and fix data types, ....


2️⃣ Exploratory Data Analysis (EDA)  
1. Explored and analyzed the procurement dataset to understand purchasing behavior, vendor performance, delivery efficiency, and cost optimization opportunities.
2. Read and examined the structure of each table, identified relationships between datasets, and selected key fields required for business analysis.
3. Performed analytical exploration to detect:
 - Purchasing trends over time
 - Vendor performance differences
 - Lead time inefficiencies
 - Shipping performance issues
 - Rejection patterns
4. Compared vendors using metrics such as:
- Total Spend
- Lead Time
- On-time Delivery Rate
- Reject Rate
- Unit Price Differences
- Potential Savings
5. Identified key business insights and analytical directions used to design dashboards and support procurement decision-making.
6. Validated business problems using data-driven analysis before building the final Power BI dashboards and visualizations.
   


3️⃣ Power BI Visualization  
1. Designed interactive procurement dashboards to monitor vendor performance, purchasing trends, shipping efficiency, and cost optimization opportunities.
2. Developed KPI metrics and DAX measures including Total Spend, Avg PO Value, On-time Delivery Rate, Reject Rate, Saving Opportunity, and Price Difference %,...
3. Built analytical visualizations such as trend charts, scatter plots, and  table to support procurement decision-making.
4. Implemented interactive features including slicers, conditional formatting, and dynamic filtering for better user experience.
5. Structured dashboards using a business-focused storytelling approach to highlight actionable insights and recommendations.

---

## 📊 Key Insights & Visualizations  

### 🔍 Dashboard Preview  

#### 1️⃣ Purchasing Overview
<img width="1333" height="740" alt="image" src="https://github.com/user-attachments/assets/86695f4c-4793-47bf-96a3-6bac3a128e5f" />


📌 Analysis 1:  
- Observation: _Describe trends, key metrics, and patterns._  
- Recommendation: _Suggest actions based on insights._  

#### 2️⃣ Vendor Performance
<img width="1328" height="743" alt="image" src="https://github.com/user-attachments/assets/c69d21f0-220b-47f7-946c-319952751da4" />


📌 Analysis 2:   
- Observation: _Describe trends, key metrics, and patterns._  
- Recommendation: _Suggest actions based on insights._  

#### 3️⃣ Price Optimazation  
<img width="1328" height="742" alt="image" src="https://github.com/user-attachments/assets/4b1aab60-9094-406c-93d1-c533bf95d63e" />



📌 Analysis 3:  
- Observation: _Describe trends, key metrics, and patterns._  
- Recommendation: _Suggest actions based on insights._  

---

## 🔎 Final Conclusion & Recommendations  

👉🏻 Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following:  

📌 Key Takeaways:  
✔️ Recommendation 1  
✔️ Recommendation 2  
✔️ Recommendation 3


---
<p align="center">
  <img src="https://github.com/user-attachments/assets/d007d335-052f-481d-8e10-818c86061478" alt="purchasing-concept">
</p>



# 📊 Project Title: Purchasing Performance Analysis (Power BI)
Author: Nguyễn Văn Trí


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

✔️ Are we maintaining sufficient inventory levels to support sales without stockouts or quality-related shortfalls?  
✔️ Are vendors delivering orders on time, and where are the delays occurring?  
✔️ Are we purchasing at optimal prices, and where are the biggest cost-saving opportunities?


### 🎯Project Outcome:  

✔️ Sufficient Inventory (Quality/Supply): 12.64% of orders experienced a quality issue, concentrated in just 11 of 86 vendors — the problem is manageable through targeted vendor review.
✔️ On-time Delivery: 99.95% of orders delivered on time overall, with issues isolated to a single shipping method (OVERSEAS - DELUXE) and a single vendor exceeding its committed lead time (Jeff's Sporting Goods).
✔️ Optimized Procurement Cost: $889,978 in potential savings is highly concentrated in one vendor relationship — Premier Sport, Inc.  accounts for 39% of the total opportunity.

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
<img width="1330" height="743" alt="image" src="https://github.com/user-attachments/assets/a4f3a8c8-1268-44d9-9250-ca4e20615108" />


📌 Analysis 1:  
- Observation:   
  + Total purchasing spend reached $70.48M across 4,012 purchase orders, showing a high level of procurement activity.    
  + Vendor delivery performance was generally strong, with an on-time rate of 99.95% and an average lead time of 9 days.    
  + 12.64% of purchase orders (507/4,012) contained at least one rejected item, with Components showing the highest reject rate among classified categories (3.45%).  
  + 56% of purchasing spend currently lacks category classification, limiting the reliability of category-level analysis and Components is the largest classified category at $26.7M.      
- Recommendation:
  + Closely monitor vendors with high reject rates to improve product quality.   
  + Some products are currently uncategorized and should be assigned to appropriate categories to improve spend analysis accuracy.   
  + Prioritize vendor reviews for categories with both high spend and high reject rates.  
  
#### 2️⃣ Vendor Performance
<img width="1329" height="746" alt="image" src="https://github.com/user-attachments/assets/aa1184c9-f294-4a66-ba59-8582fb4ca55b" />


📌 Analysis 2:   
- Observation:   
  + All active vendors (86) except one achieved a perfect 100% on-time delivery rate; Integrated Sport Products recorded a 75% on-time rate and the highest average lead time (25 days) among its orders; both driven by a single severely delayed shipment.
  + 11 of 86 vendors (12.8%) showed reject rates above 5%, indicating quality issues concentrated in a specific subset of vendors rather than spread evenly.  
  + Average lead time was stable at ~9 days for most vendors, but a small group of low-volume vendors (1-4 orders each) showed lead times up to 25 days.
  + The OVERSEAS - DELUXE shipping method showed lower on-time performance (98.75%) compared to all other methods, which achieved 100%.      
- Recommendation:
  + Flag "Integrated Sport Products" for immediate review — it is the only vendor showing issues on both on-time delivery and lead time simultaneously.  
  + Review the 11 vendors (of 86) with reject rates above 5% and strengthen supplier evaluation processes for this group.  
  + Investigate the OVERSEAS - DELUXE shipping method specifically to understand the cause of its lower on-time performance and improve logistics efficiency.
  + Use vendor metrics such as reject rate, lead time, and pricing together to support supplier selection decisions, rather than relying on any single metric alone.
    
#### 3️⃣ Price Optimazation  
<img width="1333" height="743" alt="image" src="https://github.com/user-attachments/assets/7355ced0-c2d1-4422-8606-38b1d3d7197d" />



📌 Analysis 3:  
- Observation:   
  + For the selected product, potential savings can reach up to $10.5K (5.26% of spend) when purchased at the lowest available vendor price — illustrating the scale of savings achievable through vendor price comparison.   
  + Price differences between vendors for the same product can be significant — Premier Sport, Inc shows the highest overpricing at 32.15% above the best available price.  
  + Saving opportunities are highly concentrated: Touring Rim accounts for $346.5K — 39% of the company's total $889,978 potential savings.
  + Freight costs remain efficient and stable at ~2.5% of order value across most shipping methods, with OVERSEAS - DELUXE actually showing the lowest rate (2.35%) — indicating no major freight inefficiency to address.   
- Recommendation:
  + Prioritize negotiation with Premier Sport, Inc first — it shows both the highest price gap (32.15%) and the largest dollar impact ($346.5K via Touring Rim).
  + Focus cost-optimization efforts on the small set of high-impact products (led by Touring Rim) rather than spreading attention evenly across the full catalog. 
  + No action needed on freight structure at this time — current rates are already consistent and efficient across shipping methods.

---

## 🔎 Final Conclusion & Recommendations  

👉🏻 Based on the insights and findings above, we would recommend the Stakeholder team to consider the following:  
✔️ Product quality remains mostly reliable — only 12.64% of orders (507/4,012) contained a rejected item, and reject rates above 5% were concentrated in just 11 of 86 active vendors.  
✔️ Delivery performance is excellent overall — 99.95% of orders arrived on time, with the only exceptions being Integrated Sport Products (75% on-time, 25-day lead time) and the OVERSEAS - DELUXE shipping method (98.75% vs. 100% for all others).  
✔️ Cost savings potential ($889,978, or 1.40% of total spend) is highly concentrated rather than evenly spread — a single product Touring Ri purchased from Premier Sport, Inc accounts for 39% of the total opportunity ($346.5K) alone.  
📌 Key Takeaways:  
✔️ Keep tracking vendor performance regularly through key metrics like on-time delivery, reject rate, lead time, and pricing to quickly identify potential issues.       
✔️ Open renegotiation with Premier Sport, Inc first and prioritize cost-reduction efforts on high-impact products like Touring Rim rather than spreading attention evenly across the catalog.  
✔️ Strengthen supplier evaluation specifically for the 11 vendors with reject rates above 5%, and flag Jeff's Sporting Goods" for immediate review — it shows the highest lead time gap versus plan (+6.5 days, actual 25 vs. planned 18.5) among all 86 vendors.  
✔️ Continue monitoring OVERSEAS - DELUXE and overall vendor concentration, while maintaining current freight practices — these are already cost-efficient and do not require intervention at this time.  

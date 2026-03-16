# 📌 YCB Credit_Card Dashboard
Analysed and generated insights for York City Bank - Credit Card using 'Power BI' 

### 1. Project Details:
- Client - York City Bank Inc. Vermont (U.S) 
- Dataset - January to December 2025
- Segment - Credit Card

YCB Client wants a detail 'Visual Reports' on their Credit Card sales for the financial year (FY) 2025.   
Our team needs to provide a dashboard report with in-depth insights & analysis. 
It will help our client to prepare & make strategic decisions for their upcoming market 2026. 

### 2. Problem Statement:
Need to gather data from right sources.
Then design & analyze a comprehensive weekly Credit Card dashboard to generate ‘Real Time’ insights.
- All data will be segregated into weeks such as Week 1, Week 2, Week 3, and so on
- Categorize into Quarters – Q1, Q2, Q3, Q4
- To understand key performance metrics & trends.
  
This will enable key stakeholders to monitor & analyze the CC operations effectively.

### Interactive Dashboard Link:
- [Click here to View](https://app.powerbi.com/groups/me/reports/a279e09f-b6c5-4fb8-9bb7-84f847938e58/f08df47f646660abe7b7?experience=power-bi)

### 3. Extraction of Data (ETL Process):
Data are imported to SQL Database and transformed for meaningful analysis - 
Preparing the csv files 
- Creating Databases (cc_db)
- Creating tables (Customers, CC)
- Inserting the values
Later the files are exported from MySQL database to Power BI for further transformation and analysis. 

### 4. Data Processing & DAX Measures:
After importing data into Power BI, the 'Data' was cleaned & transformed in Power query

Created Column measures – Age_Group, Income_Group, Revenue

Created DAX Measures to get more detailed insights –
- Current_week rev
- WoW_revenue %, etc. 

### 5. Dashboards:
Created dashboard for visualizations using – Bar chart, Matrix table, Slicers, etc.

![CC Trans Report](https://github.com/user-attachments/assets/7b46604d-0698-46a9-bf16-f980bb4ba576)


![CC Customer Report](https://github.com/user-attachments/assets/b4c34d94-032e-4a76-9b7a-adba8a47df93)

### 6. Insights: 
- Total Revenue (in 2025) – 56.52 Million (£)
#### WoW change:
- Revenue increased by 28.8%
- Total Transaction Amt increased by 2.2 %

#### Overview YTD:
- Total interest – 7.98 M
- Total transaction amount - 45.5 M
- Male customers are contributing more in revenue 31M, female 26M
- Blue & Silver CC had top contribution (93% overall)
- TX, NY & CA is contributing to 68.81%
- Overall Delinquent rate - 6.06%
      - With self employed customer contributing at 1.66%

# Author & Contact 

👩‍💻 Author: Pragyan Saikia

📧 Email: [pragyan.saikia04@gmail.com]

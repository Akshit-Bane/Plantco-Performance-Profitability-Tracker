# Plantco Performance Profitability Tracker
A Power BI dashboard designed to identify sales growth opportunities and geographical pain points using dynamic YTD financial tracking
# PlantCo Performance Dashboard 🌿

## Overview
This repository contains an end-to-end Power BI performance report built for a fictional company, "PlantCo." The dashboard tracks financial health by analyzing Sales, Quantity, and Gross Profit, while identifying geographical pain points and growth opportunities.

## The Data
The project uses a mock dataset (`Plant_DTS.xls`) structured into three tables
* **Plant_FACT:** 2,440 rows of transactional sales data
* **Accounts:** 1,744 entries of account details and geographical data
* **Plant_Hierarchy:** 1,000 rows of product classifications

## Key Features & Techniques
* **Data Modeling:** Built a Star Schema connecting Fact and Dimension tables.
* **DAX & Time Intelligence:** Created custom measures to compare Year-to-Date (YTD) versus Prior Year-to-Date (PYTD) performance.
* **Dynamic Visuals:** Implemented a switch measure to let users toggle between Sales, Quantity, and Gross Profit % on the dashboard.
* **Account Segmentation:** Designed a scatter chart to segment accounts based on their profitability to guide sales strategies.

## Dashboard Preview
<img width="1356" height="727" alt="image" src="https://github.com/user-attachments/assets/37c292ce-c199-4f02-8d0a-aa0c640bb3b9" />

# HR Turnover Dashboard (Kaggle → Power BI)

## Overview
This project demonstrates how to build a clean HR Turnover Dashboard with relatively little effort.  
The workflow consists of three steps:
1. **ETL in Python (Kaggle Notebook)** – Data cleaning and feature engineering with Pandas/NumPy  
2. **Data Modeling in Power BI** – Star schema with fact and dimension tables  
3. **Visualization in Power BI** – Dashboard with overview, deep-dive and drillthrough pages  

## Repository Structure
- `notebooks/01_kaggle_etl.ipynb` → ETL steps in Python (Pandas, NumPy)  
- `data/hr_clean.csv` → cleaned dataset for Power BI  
- `pbix/Turnover_Dashboard_HR.pbix` → final Power BI dashboard  
- `reports/screenshots/` → example visuals from the dashboard  
- `DAX_measures.md` (optional) → overview of all DAX measures used  

## Data Source
Original dataset: [IBM HR Analytics Attrition & Performance (Kaggle)](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
Only the cleaned CSV file is included here; raw data can be downloaded from Kaggle.  

## How to Use
1. Download or clone the repository  
2. Open `pbix/Turnover_Dashboard_HR.pbix` in Power BI Desktop  
3. Explore the dashboard (slicers are synchronized across pages)  

## Notes
- Age, tenure and income bands require manual "Sort by column" activation in Power BI  
- Standard Power BI tooltips were used (no separate tooltip page created)  

## License
MIT License

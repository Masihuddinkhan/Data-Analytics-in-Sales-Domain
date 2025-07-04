# Data-Analytics-in-Sales-Domain
Analyze historical sales data of Acme Co. (USA) to identify revenue and profit drivers, seasonal trends, and business risks using a full data pipeline: SQL → Python → Power BI.

## 🚀 Project Goal

To uncover key insights from Acme Co.’s 2014–2018 sales data that can:
- Identify top-performing **products**, **channels**, and **regions**
- Reveal **seasonal trends**, outliers, and budget mismatches
- Enable data-driven decisions on **pricing**, **promotions**, and **market expansion**
- Reduce revenue **concentration risk** by segment-wise diversification

---

## 🔧 Tech Stack & Workflow

| Stage         | Tools Used        | Description |
|---------------|------------------|-------------|
| **ETL**       | SQL (MySQL / MSSQL) | Extracted raw sales data, transformed schema, handled missing budgets |
| **Data Processing** | Python (Jupyter, Pandas, NumPy) | Data cleaning, type correction, and preprocessing |
| **Exploratory Data Analysis** | Python (Matplotlib, Seaborn) | Univariate, bivariate, time-series, outlier analysis |
| **Data Storage & Updates** | SQL | Processed data stored and queried via SQL for dashboard refresh |
| **Dashboarding** | Power BI | Interactive sales dashboard with auto-refresh from SQL DB |

---

## 📈 Project Summary

This EDA-driven project dives into Acme Co.’s USA sales from 2014 to 2018. Key analysis includes:

- **Data Profiling & Cleaning:** Schema verification, missing budget handling, type corrections  
- **Univariate & Bivariate Analysis:** Revenue, margin, and price distributions across products, regions, and channels  
- **Seasonal Trend Analysis:** Identified recurring spikes/dips via monthly/yearly sales patterns  
- **Outlier Detection:** Spotted extreme transactions in revenue/unit price  
- **Customer Segmentation & Correlation:** Clustered customers by revenue vs. margin; analyzed cross-metric relationships  
- **Performance vs Budget:** Measured actual performance against budget allocations  

---

## 📊 Power BI Dashboard

The Power BI dashboard dynamically connects to the SQL database and updates insights as new data is added. It includes:

- Sales by Region / Channel / Product
- Profit vs Revenue comparison
- Budget vs Actual analysis
- Seasonality trends
- High-value customer segments
- 

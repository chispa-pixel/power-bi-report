# Plant Co. Quantity Performance Dashboard 2023

## 📊 Project Overview
This project delivers an interactive **Power BI dashboard** to analyze Plant Co.'s **Quantity Performance** for 2023.  
The goal is to move from static reports to visual, dynamic dashboards that allow managers to track performance across **time, countries, products, and profitability**.  

The dashboard compares **Year-to-Date (YTD)** against **Previous Year-to-Date (PYTD)** and provides insights into **Gross Profit %, regional performance, product mix, and account segmentation**.

---

## 🗂 Key Features
- **KPI Cards**: Track YTD, PYTD, YTD vs PYTD variance, and Gross Profit %.  
- **Regional Analysis**: Treemap of bottom 10 countries by YTD vs PYTD performance.  
- **Time Series**: Monthly comparison of YTD vs PYTD to identify trends and seasonality.  
- **Waterfall Chart**: Month-to-month growth or decline contribution.  
- **Product Breakdown**: Quantity per product type (Indoor, Outdoor, Landscape).  
- **Profitability Segmentation**: Scatter plot of accounts by Quantity vs GP%.  

---

## 💡 Business Request
**Steven – Operations Manager:**  
> We need to improve our performance reports and move from static Excel sheets into visual dashboards.  
> The focus is on how much quantity we sell, by product type, by country, and how it compares year over year.  
> We also want to track profitability (GP%) and have the ability to filter by regions and products.  

---

## 📌 Business Demand
- **Reporter:** Steven – Operations Manager  
- **Value of Change:** Visual dashboards for Quantity & Profitability analysis, improved tracking of performance across time, products, and geographies.  
- **Systems Used:** Power BI, ERP System (Quantity Data), Excel (Budget / Reference).  
- **Other Relevant Info:** Focus on YTD vs PYTD, profitability segmentation (GP%), and filtering by country and product type.  

---

## 👤 User Stories
| No | As a (role)        | I want (request / demand)                        | So that I (value)                               | Acceptance Criteria |
|----|---------------------|-------------------------------------------------|------------------------------------------------|---------------------|
| 1  | Operations Manager | Dashboard overview of quantity sold vs PYTD      | Track growth and performance year over year     | Power BI dashboard with YTD vs PYTD KPIs |
| 2  | Regional Manager   | Quantity breakdown by country                    | Identify underperforming or outperforming areas | Treemap/table showing country performance |
| 3  | Product Manager    | Overview of quantity per product type            | Monitor product performance (Indoor/Outdoor/etc.) | Filterable product view |
| 4  | Finance Manager    | Profitability segmentation by GP% and Quantity   | Identify profitable and non-profitable accounts | Scatter plot of GP% vs Quantity |
| 5  | Operations Manager | Monitor performance trends over time             | Identify seasonality and monthly variations     | Monthly chart with YTD vs PYTD lines |

---

## 🔍 Insights
- **Overall Growth:** YTD vs PYTD shows +17.05K, with current S_YTD at **555.66K** vs **538.61K** last year.  
- **Countries:** China (-9.76K), France (-9.36K), and Sweden (-6.71K) show the largest negative variance.  
- **Monthly Trends:** Strong growth in April (+12K) and May (+5K), but declines in July (-7K) and August (-8K).  
- **Profitability:** GP% at **39.62%**. Most accounts cluster around 30–50% margin, but some high-volume low-margin accounts need review.  

---

## 🛠 Tools & Technologies
- **Power BI Desktop** (Data modeling & visualization)  
- **DAX** (Time Intelligence, KPIs, custom measures)  
- **Excel** (Budget data reference)  

---

## 📂 Files in Repository
- `Plant_Co_Quantity_Performance_2023.pbix` → Main Power BI report.  
- `Data/` → Source files (Excel/CSV).  
- `README.md` → Documentation (this file).  
- `Screenshots/` → Dashboard visuals for quick reference.  

---

## 👨‍💻 Author
**Omar Alejandro Martínez Cisneros**  
Data Scientist | Power BI & SQL Server | Business Analytics  

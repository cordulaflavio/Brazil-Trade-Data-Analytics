# Brazil-Trade-Data-Analytics

## 1. Introduction
This project was developed as a personal initiative to explore Brazil's international trade flows through data analytics. It provides insights into imports, exports, key products, and trading partners. Although conceived as an independent project, it has already attracted attention and generated partnership opportunities.

## 2. Reach
The dashboard was designed for data analysts, business professionals, and policymakers interested in understanding trade trends. It allows filtering by products, countries,states and time periods, enabling an exploratory analysis of Brazil's external trade.
Although it started as a personal project, its reach goes beyond individual learning. The dashboard is valuable for economists, business professionals, and policymakers interested in Brazil’s trade dynamics. It has already facilitated networking and potential partnerships.

## 3. Production Timeline
- **Data Collection:** Open data sources related to Brazil’s foreign trade.  
- **Data Preparation:** Data cleaning, structuring, and modeling for BI consumption.  
- **Dashboard Design:** Layout definition and creation of visualizations in Power BI.  
- **Final Delivery:** Export and publication of the dashboard with interactive features.
- In production since September 2025. 

## 4. Technologies Used
- **Power BI / Power Query** – Data modeling, cleaning, and transformation.  
  - Manual import of CSV datasets covering multiple years.  
  - Data transformations including pivoting, merging files, and unifying schemas.  
  - Integration of IBGE reference data to correct and update official state codes.  
- **GitHub** – Version control and portfolio hosting.  

## 5. Project Architecture
The project followed a structured workflow to transform raw CSV files into an interactive dashboard:

1. **Data Source** – Multiple CSV files containing Brazil's import and export data from different years.  
2. **Data Preparation (Power Query)**  
   - Consolidation of CSVs into a unified dataset.  
   - Data transformations: pivoting, merging, and cleaning operations.  
   - Integration of IBGE datasets to validate and update official state codes.  
3. **Data Modeling (Power BI)** – Creation of relationships, calculated columns, and measures to support analysis.  
   - The data model is available [here](images/data_model.png).  
4. **Visualization (Power BI Dashboard)** – Development of interactive reports with filters by product, country, state, and time period.  
   - Includes a navigation bar that opens a slide panel with filter options for better user exploration.

### Project Folder Structure

Brazil-Trade-Data-Analytics/
├── data/ # Raw CSV datasets
├── docs/ # Documentation, notes, or references
├── images/ # Screenshots, icons, maps, and data model image
├── icons/ # Custom icons used in the dashboard
├── maps/ # Custom map files if applicable
└── pbix/ # Power BI report files

## 6. Dashboard
![Dashboard Preview](images/dashboard.png)

The dashboard includes six pages:  

1. **Brazil Trades** – Overview of imports and exports, key indicators, and trends.  
2. **Brazil Exports** – Detailed analysis of exported products, top countries, and time trends.  
3. **Brazil Imports** – Detailed analysis of imported products, top countries, and time trends.  
4. **Brazil Trade Country Analysis** – Comparison of trade volumes by country with interactive filters.  
5. **Brazil Trade By State** – State-level trade insights, including imports and exports distribution.  
6. **State-Level Trade Analysis** – Deep dive into state-specific trends and product breakdowns.

### Dashboard Features
- **Interactive Filters** – Accessible via a navigation bar with a slide panel.  
- **Cards and KPI Indicators** – Highlight key metrics at a glance.  
- **Line Charts & Ribbon Charts** – Visualize trends and relationships between products and countries.  
- **Tables** – Display detailed trade data with sorting and filtering.  
- **Maps** – Geographic representation of trade flows and state-level data.  

Selected DAX calculations and measures can be found in the `scripts/key_dax_measures.txt` file.

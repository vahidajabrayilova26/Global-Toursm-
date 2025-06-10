
### Global Tourism and Economic Indicators Analysis (Power BI Project)
### Introduction

This project involves visual analysis of international tourism and economic indicator data using the Power BI platform. The main goal is to visually present tourism revenues, tourist arrivals, economic indicators (GDP, inflation, unemployment), and the relationships between these metrics across different countries.

### Note (Regarding Confidential Data)

Currently, in my workplace, I analyze and report on real tourism sector data. However, due to confidentiality, this project uses a publicly available sample dataset named **“World Tourism Economy Data (1999–2023)”**. The dataset covers the years 1999 to 2023 and includes the following fields:

### Dataset Fields

* **country:** Country name
* **country\_code:** ISO country code
* **year:** Reporting year
* **tourism\_receipts:** Revenue from international tourism (USD)
* **tourism\_arrivals:** Number of international tourists arriving
* **tourism\_exports:** Share of tourism in exports (%)
* **tourism\_departures:** Number of tourists departing abroad
* **tourism\_expenditures:** Spending by inbound tourists
* **gdp:** Gross Domestic Product (USD)
* **inflation:** Annual inflation rate (%)
* **unemployment:** Unemployment rate (%)

### Created Visualizations and Dashboards

**Page 1: Global Overview**

* KPI Cards:

  * Total tourism revenues 💰
  * Total tourist arrivals 🌍
  * Total tourist departures ✈️
  * Tourism’s share of GDP (%)
* Stacked Column Chart:

  * Top 10 countries by tourism revenue, tourist arrivals, and tourist expenditures
  * Presented for the year 2023
* Interactive slicers for year and country filtering

**Page 2: Trends Over Time**

* Line Chart:

  * Changes in tourism revenues from 1999 to 2023
  * Comparison among selected countries
* Dual Line Chart:

  * Inflation and unemployment trends over time
  * Monitoring economic stability’s impact on tourism

**Page 3: Economic Insights**

* Combo Chart (Line + Column):

  * Annual relationship between GDP and tourism revenues
* Matrix Table:

  * Country-wise comparison of GDP, tourism revenues, and tourist numbers with conditional formatting
* Bubble Chart:

  * GDP vs Tourism Receipts visualization
  * Bubble size indicates number of tourists
  * Related countries shown in different colors

### Analytical Approaches and Technical Details

* Used Power BI’s DAX functions to calculate:

  * Tourism % of GDP = DIVIDE(tourism\_receipts, gdp)
* Added slicers and drill-through pages to enhance user interactivity
* Used conditional formatting and tooltips for better data understanding

### Conclusion

This report enables analysis of the interrelations between tourism and economic indicators through Power BI. The methodology, filtering options, and interactive design are structured to be applicable in real-world professional environments.



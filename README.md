# Philippines Emigration (Year 1988 - 2020) Dashboard


![Emigration_Dashboard](/images/gif_record_dashboard.gif)

## Introduction
The dashboard presents analysis of registered Filipino emigrants by province, and municipality from the year 1988 to 2020. Using interactive visualizations and year based comparisons, it highlights trends, geographic distributions and changes for emigration figures over time. This aims to make historical data easier to explore and interpret, supporting data driven insights into Philippines emigration patterns.

## How Was This Data Processed?
### Data Preparation & Cleaning :

**Excel · Power Query**

- Inspected and cleaned the original dataset
    
- Standardized values and prepared regional, provincial, and municipal data
    
- Unpivoted yearly columns into a structured Year–Value format for time-series analysis

### Data Modeling :

**SQL · Data Modeling**

- Organized data into region, province, and municipality tables.
    
- Created supporting tables and columns
    
- Backfilled columns using records and linking them from existing columns 

### Relationships :

**Power BI · Power Query · Data Modeling**

- Established primary and foreign key relationships using unique identifiers
    
- Designed relationships between original and unpivoted tables to support hierarchical filtering

### Data Analysis & Calculations :

**DAX · Aggregation · Time-Series Analysis**

- Gathered totals, counts, and growth across geographic levels.
    
- Compared yearly values to identify trends and changes over time.
    
- Used measures and filter context to support interactive analysis.

### Data Visualization & Reporting :

**Power BI · Interactive Dashboards**

- Created KPI cards, charts, and yearly trend visualizations.
    
- Implemented province and municipality slicers.
    
- Designed an interactive dashboard for exploring geographic distributions and historical patterns.
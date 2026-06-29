# FNP Business Excel Data Analysis Project

## Overview

This project focuses on analysing sales performance and customer behaviour for FNP (Ferns N Petals), a retail gifting company. The dataset contains information relating to products, orders, customers, and gifting occasions.

The analysis focuses on gift purchases made during important occasions in India, including Diwali, Valentine's Day, Birthdays, and Anniversaries. The objective was to transform raw data into meaningful business insights using Excel data analysis tools.

Credits for the dataset and project inspiration go to "WsCube Tech! ENGLISH" (YouTube).


### Tools Used

* Microsoft Excel
* Power Query
* Power Pivot
* Excel Data Model
* Pivot Tables
* Slicers & Timelines

### Data Preparation Process

The following steps were performed to prepare the data for analysis:

* Imported data from multiple files containing:
  - Products
  - Orders
  - Customers

* Combined and transformed the data using Power Query Editor.
* Renamed tables and verified column data types.
* Created additional calculated columns in the orders table:
  - Extracted order month from the order date.
  - Extracted order hour from order time.
  - Calculated delivery duration in days.
  - Extracted delivery hour.

* Merged the products table with the orders table to include product pricing information.
* Loaded the transformed data into Excel and added it to the Excel Data Model.


### Data Modelling & Dashboard Development

A data model was created using Power Pivot (Diagram View).

The following steps were performed:

* Created relationships between tables.
* Added calculated columns within Power Pivot:
  - Revenue calculation
  - Day name extraction from order date

* Created interactive dashboard elements:
  - Occasion slicers
  - Timeline slicers
  - Pivot charts
  - Performance visualisations

The final dashboard allows users to explore sales performance across different time periods, occasions, products, and locations.

## Key Insights

* Revenue Performance: 
  The business generated approximately ₹3.52M in total revenue, with an average customer spending of around ₹3.5K.

* Monthly Revenue Trends: 
  Revenue showed seasonal fluctuations, with the strongest performance occurring around February and August, while lower-performing months included June and September.

* Top Products:  
  The highest revenue-generating products were Magnam Set, Orchid Set, and Dolcetto Gift, indicating strong customer demand for these products.

* Customer Locations:  
  Sales were distributed across multiple cities, with cities such as Indore and Dhanbad among the strongest contributors.

* Occasion Analysis:  
  Revenue varied across different gifting occasions, with events such as Anniversaries, Raksha Bandhan, and Birthdays contributing significantly to overall sales.

* Category Performance: 
  Categories including Colours, Soft Toys, and Sweets generated strong revenue, highlighting popular customer preferences.

* Business Recommendations:  
  The company could improve revenue consistency by focusing marketing efforts on high-performing occasions, products, and categories while developing strategies for lower-performing periods.

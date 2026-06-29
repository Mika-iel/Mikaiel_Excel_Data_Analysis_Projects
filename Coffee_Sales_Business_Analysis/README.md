# Coffee Business Analysis Project

## Overview

This project focuses on analysing sales performance and customer purchasing behaviour for a coffee shop business. The analysis explores coffee sales trends, roast type performance, customer purchasing patterns, and geographical sales distribution.

The objective was to transform raw transactional data into meaningful business insights through Excel calculations, formulas, and the development of an interactive Excel dashboard.

Credits for the dataset and project go to Mo Chen (YouTube Channel).


## Process

### Data Preparation

The dataset was cleaned and prepared for analysis:

* Checked for duplicate values (no duplicate records were identified).
* Enhanced the orders table by retrieving additional information:
  - Customer names using VLOOKUP.
  - Customer emails using VLOOKUP combined with IF statements to handle blank values.
  - Customer country using VLOOKUP.
  - Coffee type, roast type, size, and unit price using INDEX and MATCH functions.

* Excel Formula Calculations:
  - Sales calculated by multiplying unit price by quantity.
  - Full coffee type names and roast type names created using nested IF statements.
  - Loyalty card information retrieved using VLOOKUP.

* Standardised data formatting:
  - Corrected date formatting issues and converted dates into a consistent format.
  - Added "Kg" formatting to coffee size values.
  - Converted unit price and sales fields into currency format.

* Converted the orders dataset into an Excel Table to improve usability for Pivot Tables and dashboard development.


## Dashboard Development

An interactive dashboard was created using Excel tools.

The dashboard includes:

* Timeline slicer:
  - Order date filtering

* Interactive slicers:
  - Roast type
  - Coffee size
  - Loyalty card membership

* Visualisations:
  - Coffee sales trends over time using a line chart.
  - Top 5 customers based on purchase value.
  - Sales performance by country.

* Connected slicers across dashboard elements to allow interactive filtering.
* Dashboard formatting and visual improvements were applied to improve readability and presentation.


## Key Insights

* Sales Trends:  
  Coffee sales fluctuated between 2019–2022, with several periods of increased demand, suggesting seasonal changes in customer purchasing behaviour.

* Top Market:
  The United States generated the highest sales contribution compared to other countries, making it the strongest-performing market.

* Customer Behaviour:  
  A small number of customers contributed a significant portion of purchases, highlighting the importance of customer retention strategies.

* Roast Type Performance:  
  Different roast types displayed varying sales patterns, indicating differences in customer preferences.

* Product Preferences:  
  Customer purchasing patterns varied across coffee sizes, providing insights into preferred product options.

* Business Opportunity:  
  The company can improve performance by focusing on high-performing markets, understanding customer preferences, and using loyalty programmes to encourage repeat purchases.






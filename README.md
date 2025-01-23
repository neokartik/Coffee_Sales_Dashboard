# Coffee Sales Dashboard

## Project Overview

The **Coffee Sales Dashboard** is a data analysis project aimed at visualizing coffee sales trends and providing insights into various aspects of the sales process. The dashboard leverages Excel to aggregate, clean, and visualize sales data to help stakeholders make data-driven decisions. This project uses datasets related to coffee orders, customer information, and product details, focusing on coffee types, roast types, pricing, and customer behavior.

The project integrates three main datasets:

1. **Orders**: Contains data related to each coffee order, including customer details, coffee type, product details, pricing, and sales.
2. **Customers**: Contains information about each customer, such as their contact details, location, and loyalty card status.
3. **Products**: Includes details about coffee products, including their type, roast type, size, price per unit, and profit margins.

Using these datasets, the dashboard aims to provide insights into sales performance, customer behavior, popular coffee types and sizes, and the profitability of different products.

## Project Structure

The project contains the following key files:

- **orders.csv**: Contains data on each order, including:
  - Order ID
  - Order Date
  - Customer ID
  - Product ID
  - Quantity
  - Customer Name
  - Email
  - Country
  - Coffee Type (Robusta, Excelsa, Arabica)
  - Roast Type (Medium, Light, Dark)
  - Size
  - Unit Price
  - Sales
  - Coffee Type Name
  - Roast Type Name
  - Loyalty Card Status

- **customers.csv**: Contains customer details such as:
  - Customer ID
  - Customer Name
  - Email
  - Phone Number
  - Address Line 1
  - City
  - Country
  - Postcode
  - Loyalty Card Status

- **products.csv**: Contains product details such as:
  - Product ID
  - Coffee Type
  - Roast Type
  - Size
  - Unit Price
  - Price per 100g
  - Profit

## Key Features of the Dashboard

The Coffee Sales Dashboard built in Excel offers the following features:

- **Sales Analysis**: Visualizations to track total sales, sales by coffee type, roast type, and product size.
- **Customer Analysis**: Insights into customer behavior, including the number of loyal customers (those with a loyalty card) and their purchasing patterns.
- **Profitability**: A breakdown of profits by product type, coffee type, roast type, and region.
- **Popular Products**: Identify top-selling coffee types, roast types, and sizes.
- **Geographical Insights**: Breakdown of coffee sales by country and city, helping identify regions with the highest demand.
- **Trend Analysis**: Analysis of sales trends over time to spot seasonal trends or spikes in orders.

## Tools Used

- **Microsoft Excel**: Used for data analysis, cleaning, and visualization. Key features include PivotTables, charts, and advanced Excel formulas for data aggregation and transformation.
- **Data Cleaning Techniques**: Utilized Excel functions to clean and organize the raw data, ensuring accurate analysis.

## Getting Started

To use the Coffee Sales Dashboard, follow these steps:

1. **Download the Dataset Files**:
   - `orders.csv`
   - `customers.csv`
   - `products.csv`

2. **Open the Dashboard**:
   - Open the **Coffee Sales Dashboard Excel file** in Excel.

3. **Data Processing**:
   - Import the CSV files into the Excel dashboard.
   - Perform necessary data transformations using built-in Excel functions like `VLOOKUP`, `SUM`,`IF-ELSE`,`INDEX-MATCH` and conditional formatting if required.
   
4. **Visualize**:
   - Use Excel charts like bar charts, line graphs and PivotTables to create interactive and dynamic visualizations.

## Data Sources

The project relies on the following datasets:

1. **Orders Dataset**: Contains information about individual coffee orders, including the type of coffee, customer details, and sales data.
2. **Customers Dataset**: Provides demographic details about customers, which can be used to segment sales by customer attributes such as location and loyalty card status.
3. **Products Dataset**: Includes details about coffee products, helping analyze pricing, profit margins, and customer preferences for various product configurations (e.g., coffee types, roast types, sizes).


## Required Dashboard:
![image alt]()

## Conclusion

The Coffee Sales Dashboard provides valuable insights into coffee sales performance, customer preferences, and product profitability. By leveraging the power of Excel, it allows businesses to make informed decisions about inventory management, pricing strategies, and marketing campaigns.

Feel free to explore, fork, and contribute to this project!

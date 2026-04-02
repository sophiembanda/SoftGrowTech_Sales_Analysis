# SoftGrowTech Sales Analysis

## Overview
This project performs sales data analysis for SoftGrowTech. It involves loading, cleaning, and analyzing sales data to derive insights such as profits, trends, and more.

## Data
The raw sales data is stored in `sales_data.csv`. The cleaned data is saved to `Clean_sales_data.csv`.

### Data Dictionary
1. **Product_ID**: Unique identifier for each product sold.
2. **Sale_Date**: The date when the sale occurred (from 2023).
3. **Sales_Rep**: The sales representative responsible for the transaction (5 random reps).
4. **Region**: The region where the sale took place (North, South, East, West).
5. **Sales_Amount**: The total sales amount for the transaction.
6. **Quantity_Sold**: The number of units sold (1-50).
7. **Product_Category**: Category of the product (Electronics, Furniture, Clothing, Food).
8. **Unit_Cost**: Cost per unit (50-5000).
9. **Unit_Price**: Selling price per unit.
10. **Customer_Type**: New or Returning customer.

## Requirements
- Python 3.x
- pandas
- matplotlib
- Jupyter Notebook
- Power BI Desktop (for viewing the dashboard)

Install Python dependencies:
```
pip install pandas matplotlib
```

## Usage
1. Open `Sales Analysis.ipynb` in Jupyter Notebook.
2. Run the cells to load data, clean it, perform feature engineering, and save the cleaned data.
3. Analyze the results in the notebook.
4. Open `Sales_Dashboaard.pbix` in Power BI Desktop to view interactive visualizations of the sales data.

## Analysis Steps
1. **Data Loading**: Import necessary libraries and load the CSV file.
2. **Data Exploration**: Check data info, null values, and data types.
3. **Data Cleaning**: Convert dates, identify and handle errors (e.g., cost > price).
4. **Feature Engineering**: Calculate total cost, profit, extract time features (month/year, day name).
5. **Save Cleaned Data**: Export the processed data to a new CSV file.

## Files
- `sales_data.csv`: Raw sales data.
- `Clean_sales_data.csv`: Cleaned and processed sales data.
- `Sales Analysis.ipynb`: Jupyter notebook with the analysis code.
- `Sales_Dashboaard.pbix`: Power BI dashboard file for interactive data visualization.
- `anaconda_projects/db/`: (Additional project files, possibly for database integration).

## Contributing
Feel free to fork and contribute to this project.
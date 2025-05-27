# Product_Sales_ETL
I worked with a multi-table dataset involving orders, products, and customer data and completed a full data-cleaning and merging workflow using Excel formulas like VLOOKUP, INDEX-MATCH, and XLOOKUP.

📊Situation:
A dataset consisting of three related tables – orders, products, and customer – required data cleaning, transformation, and merging to ensure accurate analysis of product sales.

📊Task:

The goal was to:

📍Clean inconsistent, duplicate, and incorrectly formatted data.

📍Merge the data across all three tables using Excel formulas.

📍Create a unified and reliable dataset for further analysis.


![image](https://github.com/user-attachments/assets/b78983e9-e44b-40e2-83d7-d1512e41f474)


📊Action:

🎯Data Cleaning:🎯

📌In the orders table:

Removed duplicate entries based on order_id to prevent double counting.

Converted product_id from numeric to text format for consistent lookups.

Cleaned malformed qty entries ending in "Q", and filled missing values with "Not Available".

📌In the products table:

Trimmed leading/trailing spaces in product_name using the TRIM() function.

Extracted numeric price values from strings using the ₹ delimiter.

📌In the customer table:

Standardized customer names by converting them to lowercase and used paste special for values-only formatting.

🎯Data Merging:🎯

Merged customer_name into the orders table using VLOOKUP().

Added product_name using the INDEX-MATCH() function.

Pulled in price (in Rs) using XLOOKUP().

Calculated total_price by multiplying cleaned qty and price fields.

📊Result:

✅Achieved a clean, enriched dataset ready for visualization or further analytics.

✅Demonstrated proficiency in Excel formulas including VLOOKUP, INDEX-MATCH, XLOOKUP, and data transformation techniques.

✅Reinforced good practices in data preparation and integration using Microsoft Excel.

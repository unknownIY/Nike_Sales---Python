Data Cleaning:

Size Column: Cleaned mixed data types, mapped numerical sizes to categorical (S, M, L, XL), made values uppercase, and imputed missing values using gender-based mode.
Units_Sold Column: Corrected negative values to zero, imputed missing values using mode/median based on 'Gender_Category' and 'Product_Line', and converted to integer.
MRP Column: Imputed missing values using a predefined price_map_inr based on 'Product_Name'.
Discount_Applied Column: Filled missing values with zero and capped values greater than 1 to 0.
Order_Date Column: Converted to datetime objects, handling multiple date formats.
Revenue Column: Recalculated based on cleaned 'MRP', 'Units_Sold', and 'Discount_Applied'.

Data Visualization:

Bar plot: Total Revenue by Product_Line.
Bar plot (Plotly): Total Revenue by Product_Line and Product_Name.
Bar plot: Total Revenue by Gender_Category.
Pie chart: Sales_Channel Distribution.
Bar plot: Top 10 Products by Revenue (Product_Name).
Scatter plot: Revenue by Order_Date and Gender_Category.
Histogram (Seaborn): Revenue Distribution.
Histogram (Plotly Express): Revenue Distribution.


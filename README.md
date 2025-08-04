# Portfolio Project: E-commerce Sales Performance Analysis Dashboard

### Project Description
This dashboard was created to analyze the sales performance of an e-commerce store. It functions to transform raw, unstructured data into clear, actionable insights to support business decision-making.

### Business Problem
The e-commerce store faced challenges in understanding its sales data. The available raw data was unstructured, had missing values, and inconsistent formats. This made it difficult for the team to track key metrics and identify trends.

### Project Workflow

#### 1. Data Cleaning & Transformation (Using Power Query)
-   **Date Cleaning:** The 'OrderDate' column had inconsistent date formats. This was handled by identifying all incorrect date formats and converting them to a standard format to ensure data integrity and analytical accuracy.
-   **Handling Missing Values:** Empty values in the 'Region' column were filled with "Unknown". The 'Discount' column, which contained empty cells or text, was replaced with 0.
-   **Creating a New Column:** A calculated column 'TotalRevenue' was created with the formula 'Quantity * UnitPrice * (1 - Discount)'.

#### 2. Key Visualizations
The dashboard features the following key visualizations:
-   **KPI Cards:** Displaying key metrics such as Total Revenue and Total Sales.
-   **Line Chart:** Showing sales trends over time (yearly, monthly) to identify seasonal patterns.
-   **Bar Chart:** Highlighting the Top 5 best-selling products by revenue.
-   **Donut Chart:** Displaying the distribution of revenue by product category.
-   **Interactive Slicer:** Allowing users to filter data by a date range.

### Dashboard Screenshot
<img width="888" height="497" alt="image" src="https://github.com/user-attachments/assets/0e87a652-6431-45e8-a07d-746e8b9a487c" />

### Key Insights
-   The highest sales is USD 11,039 while the lowest is USD 41.88
-   The 'Perhiperals' category is the largest contributor to revenue holding 21.78% of sales
-   Smartphone and USB-C Hub hold the highest revenue compare to other products


### Technologies Used
-   **Power BI Desktop:** For visualization and dashboard creation.
-   **Power Query M Language:** For the data cleaning and transformation process.
-   **GitHub:** For portfolio storage and presentation.

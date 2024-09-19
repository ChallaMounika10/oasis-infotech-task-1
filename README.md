
# **Retail Sales Data Analytics Project**
## 1. Project Overview
This project focuses on analyzing a retail sales dataset to uncover valuable insights into sales patterns, customer behavior, and inventory management. By leveraging various exploratory data analysis (EDA) techniques and advanced visualizations, this project aims to provide actionable recommendations that can help improve business decisions and optimize retail operations.

## 2. Data Description
The dataset used in this project includes sales transactions with columns such as data (date of sale), venda (sales amount), estoque (inventory or product identifier), and preco (price of the product). This dataset provides a comprehensive view of sales performance, inventory distribution, and pricing strategies over time.

## 3. Data Cleaning
The data cleaning process involves several key steps: converting the data column to datetime format, handling missing values, and ensuring data integrity. Missing values are addressed through methods such as forward filling or dropping rows/columns with missing entries. Proper data cleaning is crucial for accurate analysis and reliable insights.
## 4. Descriptive Statistics
Descriptive statistics provide a summary of the dataset's key characteristics. Measures such as mean, median, mode, and standard deviation are calculated for sales, inventory, and price. These statistics help in understanding the central tendencies, variability, and distribution of the data, offering a foundational overview of the dataset.
## 5. Time Series Analysis
Time series analysis focuses on examining sales trends over time. By resampling data on a monthly basis, we visualize sales trends and identify patterns or anomalies. Seasonal decomposition further breaks down the time series into trend, seasonal, and residual components, providing insights into underlying patterns and seasonal effects.

## 6. Forecasting with Holt-Winters Exponential Smoothing
Forecasting aims to predict future sales based on historical data. The Holt-Winters Exponential Smoothing model is used to forecast sales with consideration for both trend and seasonality. This forecasting helps in anticipating future sales and planning inventory accordingly.
## 7. Customer and Product Analysis
This analysis involves exploring sales patterns across different products (inventory) and price points. By grouping sales data by inventory and price, we generate insights into which products and price ranges are most profitable. This information is valuable for inventory management and pricing strategies.

## 8. Visualization: Heatmap of Sales by Inventory and Price
A heatmap provides a visual representation of sales data across different inventory items and price ranges. By segmenting the data into smaller parts for better visibility, the heatmap helps in understanding the relationship between inventory and pricing, highlighting areas of high and low sales.


## 9.  Additional Visualizations
Several advanced visualizations enhance the analysis, including:

Sales Over Time: A line plot showing how sales trends change over time.

Box Plot: Detects outliers in sales, inventory, and price data.

Sales Distribution by Month: Displays sales variations across different months.

Count Plot for Inventory: Shows the distribution of products in inventory.

Sales vs. Price: A scatter plot with a regression line to explore the relationship between price and sales.

Top 10 Products by Sales: Identifies the top-performing products based on sales figures.

Pie Chart for Sales Distribution: Illustrates the sales proportion across different inventory items.

Cumulative Sales: Displays the growth of cumulative sales over time.

Violin Plot: Visualizes the distribution of sales across various price ranges.

Histogram of Inventory: Shows how inventory levels are distributed.


## 10. Recommendations
Based on the EDA and visualizations, actionable recommendations are provided. These may include optimizing inventory levels, adjusting pricing strategies, focusing on top-performing products, and planning for seasonal trends. The insights derived from the analysis can guide strategic decisions to improve retail operations and boost sales performance.

## 11. Conclusion
This data analytics project demonstrates the application of various EDA techniques and visualizations to gain a deeper understanding of retail sales data. By cleaning, analyzing, and visualizing the data, we uncover valuable insights that support informed decision-making and strategic planning. The results and recommendations are intended to help businesses optimize their operations and enhance their sales strategies.

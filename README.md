# Online Sports Retail Revenue Analysis

This project analyzes data from an online sports retail store to optimize revenue and derive insights across various metrics like pricing, reviews, traffic, and sales trends. Using SQL for querying and Python for visualization, the analysis provides a deeper understanding of the retail business performance.

## Project Summary

The main goal of this project is to leverage different datasets related to product reviews, financial information, traffic, and brand data to:
- Segment products by price category.
- Calculate revenue by brand.
- Identify trends and correlations between reviews, prices, and revenue.
- Analyze seasonal sales patterns.

### Datasets Used
1. **Product Info**: Contains product descriptions.
2. **Finance**: Includes product prices, revenue, and discounts.
3. **Traffic**: Tracks product visits over time.
4. **Brands**: Links products to their brands.
5. **Reviews**: Contains customer reviews and ratings.

## Tools and Technologies
- **SQLAlchemy**: For creating and managing the SQLite database.
- **Pandas**: For data manipulation and processing.
- **Matplotlib**: For visualizing trends.
- **SQL**: For querying and aggregating data.

## Key Analysis Steps

1. **Data Loading and Setup**: 
   Data from CSV files is loaded into an SQLite database for efficient querying.

2. **Revenue and Pricing Analysis**: 
   Products are segmented by price, and total revenue is calculated for each brand and price category (e.g., Budget, Average, Elite).

3. **Discount Analysis**: 
   The average discount per brand is calculated, identifying which brands offer the highest discounts.

4. **Review and Revenue Correlation**: 
   A Pearson correlation analysis reveals a strong relationship (0.65) between product reviews and revenue.

5. **Monthly Sales Trends**: 
   Sales and revenue are aggregated by month to identify seasonal trends and peak periods of activity.

6. **Product Segmentation**:
   Footwear and non-footwear products are analyzed separately to understand their contribution to overall revenue.

## Results and Insights
- **Revenue Optimization**: Adidas and Nike show significant revenue differences across price categories, with "Elite" products generating the highest revenue.
- **Seasonal Sales Trends**: Monthly analysis highlights peak periods of customer activity, providing insights for inventory planning.
- **Review Influence**: Products with more reviews tend to generate higher revenue, suggesting a strong link between customer feedback and sales performance.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your_username/online-sports-retail-analysis.git
    cd online-sports-retail-analysis
    ```

2. **Install dependencies**:
    ```bash
    pip install pandas sqlalchemy matplotlib
    ```

3. **Run the analysis** in Jupyter Notebook or Python.

## Conclusion

This analysis provides valuable insights into product performance and customer behavior, allowing businesses to optimize their strategies for pricing, discounts, and product launches.

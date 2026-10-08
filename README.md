# E-Commerce Sales & Customer Analytics

This project analyzes e-commerce sales data to understand sales performance, profitability, customer behavior, product performance, regional performance, sales channels, payment methods, shipping methods, discounts, customer ratings, and monthly sales trends.

## Project Objective

The objective of this project is to analyze e-commerce sales data and understand the overall business performance. The analysis focuses on sales, profit, customers, products, regions, sales channels, payment methods, shipping methods, discounts, customer ratings, and monthly trends.

The main goal is to find important business patterns, identify areas of improvement, and provide useful recommendations for better business decision-making.

## Business Problem

The company wants to understand how its e-commerce business is performing and which areas are contributing more to sales and profit.

The analysis will help answer questions such as:

- Which category generates the highest sales and profit?
- Which products are performing well?
- Which region generates the highest sales and profit?
- How are new and returning customers performing?
- Which sales channel and payment method perform better?
- Which shipping method generates more sales and profit?
- How do customer ratings relate to sales and profit?
- How do discounts affect sales and profit?
- Which months have higher or lower sales and profit?

## Dataset

The dataset contains e-commerce order information with details about customers, products, sales, profit, regions, sales channels, payment methods, shipping methods, discounts, and customer ratings.

### Dataset Details

- **Total Orders:** 4,961
- **Unique Customers:** 800
- **Unique Products:** 25
- **Product Categories:** 5
- **Regions:** 4
- **Sales Channels:** Marketplace, Mobile App, Website
- **Payment Methods:** Cash on Delivery, Credit Card, Debit Card, Net Banking, UPI
- **Customer Types:** New, Returning
- **Shipping Types:** Standard, Express, Same Day
- **Customer Ratings:** 1 to 5
- **Discount Range:** 0% to 35%

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel

## Data Cleaning

The dataset was checked and cleaned before performing the analysis.

The following cleaning steps were performed:

- Checked the number of rows and columns.
- Checked the data types of all columns.
- Checked missing values.
- Checked duplicate records.
- Removed duplicate records.
- Checked for zero quantity values.
- Removed records where the quantity was zero.
- Converted the `Order_Date` column into date format.
- Checked the values of important columns such as Sales, Profit, Discount, and Customer Rating.
- Standardized the Sales Channel values.
- Created the Month column for monthly analysis.

After cleaning, the dataset contained **4,961 records**.

## Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the data and find important patterns.

The analysis included:

- Overall sales and profit analysis.
- Category-wise sales and profit analysis.
- Region-wise sales and profit analysis.
- Product-wise sales and profit analysis.
- Customer type analysis.
- Sales channel analysis.
- Payment method analysis.
- Shipping method analysis.
- Customer rating analysis.
- Discount analysis.
- City-wise analysis.
- Monthly sales and profit analysis.

Different charts were used to make the analysis easier to understand and identify important business patterns.

## Business Analysis

The business analysis was performed to understand which areas are performing well and which areas need improvement.

The following areas were analyzed:

- Category Performance
- Regional Performance
- Product Performance
- Customer Performance
- Sales Channel Performance
- Payment Method Performance
- Shipping Performance
- Customer Rating Performance
- Discount Performance
- Monthly Performance

The analysis compared sales, profit, number of orders, average sales, average profit, and profit margin wherever required to understand business performance.

## Key Business Insights

- Electronics is the highest performing category in terms of both sales and profit.
- West region generates the highest sales and profit among all regions.
- Laptop is the top-selling product based on total sales.
- Returning customers generate higher total sales and profit compared to new customers.
- Marketplace generates the highest sales and profit among the sales channels.
- Credit Card generates the highest sales and profit among the payment methods.
- Standard shipping generates the highest sales and profit among the shipping methods.
- Customers with higher ratings generate higher sales and profit in this dataset. This shows that customer satisfaction is an important area for the business to monitor.
- May has the highest total sales and profit, while July has the lowest total profit.
- The 10% discount level has the highest total sales in the dataset, but discount performance should also be considered with the number of orders because total sales depend on order volume.

## Business Recommendations

Based on the analysis, the following recommendations can be given:

- Focus more on the Electronics category because it generates the highest sales and profit.
- Maintain good stock and promotion for high-performing products like Laptop.
- Focus on improving sales in the East region through better marketing and offers.
- Try to retain returning customers by using loyalty programs and personalized offers.
- Continue focusing on the Marketplace channel and improve the Website customer experience.
- Continue supporting Credit Card payments because it generates the highest sales and profit.
- Standard shipping is an important shipping option because it generates the highest sales and profit.
- Improve customer satisfaction by focusing on product quality, customer service, and resolving customer issues.
- Monitor monthly sales and profit trends and use offers or marketing campaigns during weaker months.
- Review discount performance along with order volume and profit before deciding future discount strategies.

## Project Structure

```text
E-Commerce Sales & Customer Analytics/
│
├── 01_Data_Cleaning.ipynb
├── 02_EDA_Analysis_practice.ipynb
├── 03_Business_Insights.ipynb
│
├── Ecommerce_Sales_Analytics_Uncleaned.csv
├── Ecommerce_Sales_Analytics_Cleaned.csv
│
├── README.md
└── requirements.txt

## Conclusion

This project helped me understand the overall performance of the e-commerce business by analyzing sales, profit, customers, products, regions, sales channels, payment methods, shipping methods, customer ratings, discounts, and monthly trends.

The analysis showed that Electronics and Laptop are strong performers, while West region and Marketplace contribute strongly to the business. The project also identified areas that need improvement, such as the East region, Website channel, and low-performing products.

These insights can help the business make better decisions related to marketing, customer retention, product strategy, and business growth.
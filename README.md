# AMAZON_PRODUCT_REVIEW
 
## Project Overview 
This Data analysis project aims at analysing product and customer review data to generate insights that can guide product improvements, marketing strageies and customers engagement.
## Dataset Description 
The dataset contains information scraped from Amazon product pages, including: 
* Product details: name, category, price, discount, and rating
* Customer engagement: user review, titles, and content
* Each row represents a unique product, with aggregated reviewer data stored as comma-separated value
  - Total Records: 1,465 Rows
  - Total Fields: 16 Columns
## Tools used
+ Microsoft Excel (for data cleaning and visualization)

## Cleaning Steps
Load data to Excel query editor
* Slipt column by delimeter to separate values, to obatain Product_Category
* Slipt column by character to separate values, to obtain Product_ID

## Calculated Columns
Created four new columns to enhance analysis:
 1. Price Bucket
    Categorized proucts into price range (e.g $200 - 500, > $500) based on discounted price.
 2. Potentail Revenue 
    Estimated revenue using the formula (Potential Revenue = Discounted price * rating count)
## Analysis Tasks
Analysis Tasks
The project involves various analysis tasks, including;

- Average discount percentage by product category
- Product count by category
- Total reviews per category
- Products with highest number of reviews
- Distribution of product ratings
- Potential revenue by category
- Unique products per price range bucket
- Relationship between rating and discount level
- Products with fewer than 1,000 reviews
- Categories with highest discounts
- Top 5 products in terms of rating and number of reviewed combined

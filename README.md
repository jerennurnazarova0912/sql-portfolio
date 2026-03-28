# Amazon Sales Data Analysis 📊

## Project Overview
This project focuses on processing and structuring a comprehensive dataset of Amazon sales, including product details, pricing, and customer ratings. The goal was to build a robust database schema in **PostgreSQL** to enable deep-dive analysis into e-commerce trends.

## Technical Skills Demonstrated
* **Database Schema Design:** Created structured tables with appropriate data types (`VARCHAR`, `TEXT`, `NUMERIC`).
* **Data Integration:** Managed large-scale data imports using the `COPY` command.
* **Data Cleaning:** Handled complex strings and formatted pricing data for analysis.

## Database Schema
The main table `amazon_sales` includes the following key attributes:
* `product_id`, `product_name`, `category`
* `discounted_price`, `actual_price`, `discount_percentage`
* `rating`, `rating_count`
* `about_product`, `user_id`, `user_name`

## How to Run
1. Ensure you have **PostgreSQL** installed.
2. Run the `amazon_project.sql` script to create the table.
3. Import the dataset using the provided `COPY` command (update the file path accordingly).

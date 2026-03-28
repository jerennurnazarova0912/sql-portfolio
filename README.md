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






---

---

# HSBC Loan Analysis 🏦

## Project Overview
This project focuses on designing and implementing a robust database schema to analyze personal loan applications for **HSBC**. The primary goal is to structure borrower demographics and financial data to support automated credit risk assessment and decision-making processes.

## Technical Skills Demonstrated
* **Database Schema Design:** Engineered a relational structure specifically for banking operations.
* **Optimized Data Types:** Implemented precise data types (`VARCHAR`, `INT`) to ensure storage efficiency for financial identifiers.
* **Data Integrity:** Enforced `PRIMARY KEY` constraints to maintain unique records and prevent data duplication.

## Database Structure
The `hsbc_loan_analysis` table includes:
* `loan_id`: Unique identifier for each loan application.
* `gender` & `married`: Key demographic indicators for borrower profiling.
* `dependents`: Numerical data on household size to assess financial commitments.
* `education`: Educational background used as a proxy for earning potential and creditworthiness.

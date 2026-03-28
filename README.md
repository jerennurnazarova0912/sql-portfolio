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

# HSBC Loan Analysis 🏦

## Project Overview
Этот проект посвящен проектированию базы данных для анализа заявок на персональные кредиты в **HSBC**. Основная цель — структурировать данные о заемщиках для оценки кредитных рисков.

## Technical Skills
* **Database Design:** Создание структуры таблиц для банковских операций.
* **Data Types:** Использование оптимальных типов данных для финансовых идентификаторов.
* **Integrity:** Настройка первичных ключей (`PRIMARY KEY`) для исключения дубликатов.

## Database Structure
Таблица `hsbc_loan_analysis` включает:
* `loan_id`: Уникальный номер кредита.
* `gender` & `married`: Демографические данные заемщика.
* `dependents`: Количество иждивенцев.
* `education`: Уровень образования для оценки платежеспособности.

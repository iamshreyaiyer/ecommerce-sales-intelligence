# E-commerce Sales and Operations Intelligence

## Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset by Olist to evaluate sales performance, product category contributions, delivery reliability, regional delivery patterns, and customer satisfaction.

Using Python and data analysis libraries, this project transforms raw e-commerce data into business insights and practical recommendations.

## Business Objectives

- Evaluate overall sales performance and identify leading product categories.
- Measure delivery duration and assess late-delivery rates.
- Investigate the relationship between delivery delays and customer satisfaction.
- Identify Brazilian states and purchase months with elevated late-delivery rates.
- Recommend areas for further operational investigation.

## Tools and Technologies

- **Python** — data analysis
- **pandas** — data cleaning, transformation, and aggregation
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Google Colab** — notebook development

## Key Findings

### 1. Sales Performance

- Total orders recorded: **99,441**
- Delivered orders: **96,478**
- Product sales value associated with delivered orders: approximately **R$13.22 million**

*Product sales value is not the same as profit.*

### 2. Product Category Performance

- **Health & Beauty** ranked first in product sales value, contributing approximately **R$1.23 million**.
- **Watches & Gifts** ranked second, with approximately **R$1.17 million**.
- **Bed, Bath & Table** recorded the highest item count among the top 10 categories analyzed.

### 3. Delivery Performance

- Average delivery time: **12.56 days**
- Median delivery time: **10.22 days**
- Late-delivery rate: **8.11%** of eligible delivered orders

The difference between the average and median delivery times suggests that some longer deliveries pull the average upward.

### 4. Customer Satisfaction

- Average review score for late deliveries: **2.57/5**
- Average review score for on-time or early deliveries: **4.29/5**

Orders delivered late were associated with substantially lower review scores. This relationship does not, by itself, prove that delivery delays caused lower customer satisfaction.

### 5. Regional and Monthly Patterns

- Alagoas had the highest late-delivery rate among states with at least 100 eligible orders.
- São Paulo had the largest absolute number of late deliveries.
- March 2018 recorded a late-delivery rate of **21.36%** among eligible orders purchased that month.

These patterns identify areas for further investigation; the analysis does not establish the underlying causes.

## Business Recommendations

1. **Investigate delivery delays:** Examine fulfillment and logistics records to identify potential sources of late deliveries.
2. **Prioritize regional analysis:** Investigate states with high late-delivery rates and states contributing large numbers of late deliveries.
3. **Monitor delivery trends:** Track monthly late-delivery rates alongside order volumes to identify unusual changes.
4. **Understand customer dissatisfaction:** Review low-rated orders to investigate whether delivery delays, product issues, or other factors may contribute.
5. **Measure improvements:** Monitor late-delivery rate, median delivery time, and average review score over time.

## Project Workflow

1. Loaded and explored the available datasets.
2. Checked data types, missing values, and duplicate records.
3. Prepared data for sales and delivery analysis.
4. Analyzed sales trends and product category performance.
5. Calculated delivery duration and late-delivery rates.
6. Compared customer review scores across delivery groups.
7. Examined regional and monthly delivery patterns.
8. Summarized findings and developed business recommendations.

## Dataset

This project uses the **Brazilian E-Commerce Public Dataset by Olist**, available on Kaggle.

The dataset contains information about e-commerce orders, customers, products, sellers, payments, reviews, and delivery dates.

**Dataset source:** Brazilian E-Commerce Public Dataset by Olist on Kaggle.

**License:** CC BY-NC-SA 4.0. Please refer to the original dataset page and license terms before redistributing the data.

## Limitations

- The analysis identifies associations and patterns; it does not establish causation.
- Product sales value should not be interpreted as profit because product costs and other expenses were not analyzed.
- Delivery findings are based on eligible records with the necessary dates available.
- Regional and monthly patterns indicate where further investigation may be useful but do not establish the reasons for delays.

## Conclusion

This project demonstrates how Python-based exploratory data analysis can support business decisions by identifying sales patterns, evaluating delivery reliability, and examining the relationship between operational performance and customer satisfaction.

The findings highlight delivery reliability as an important area for further investigation because late deliveries were associated with substantially lower customer review scores.

---

**Author:** Shreya Iyer

# Sales Data Analysis

A comprehensive data analysis project analyzing sales data to extract meaningful business insights.

## Project Overview

This project analyzes sales data from January to December 2019 to answer key business questions and identify trends in consumer purchasing behavior.

## Dataset Structure

The dataset contains the following fields:
- **Order ID**: Unique identifier for each order
- **Product**: Product name
- **Quantity Ordered**: Number of units ordered
- **Price Each**: Unit price
- **Order Date**: Date and time of order
- **Purchase Address**: Customer's shipping address


## Analysis Questions

This project answers 5 key business questions:

1. **Q1: Best Month for Sales** - Which month had the highest sales?
2. **Q2: Most Product Sold by City** - Which city had the most product sales?
3. **Q3: Best Time to Advertise** - When should advertising be targeted for maximum impact?
4. **Q4: Most Sold Together** - What products are frequently purchased together?
5. **Q5: Most Sold Product** - Which product had the highest total sales?

## Project Structure

```
Sales-Data-Analysis/
├── dataset/
│   ├── Sales_April_2019.csv
│   ├── Sales_August_2019.csv
│   ├── Sales_Data_Cleaned.csv
│   ├── Sales_Data.csv
│   ├── Sales_December_2019.csv
│   ├── Sales_February_2019.csv
│   ├── Sales_January_2019.csv
│   ├── Sales_July_2019.csv
│   ├── Sales_June_2019.csv
│   ├── Sales_March_2019.csv
│   ├── Sales_May_2019.csv
│   ├── Sales_November_2019.csv
│   ├── Sales_October_2019.csv
│   └── Sales_September_2019.csv
├── script/
│   ├── data_cleanup.ipynb       # Data cleaning process
│   ├── merge_dataset.ipynb      # Merging monthly data
│   ├── q1_best_month_sales.ipynb
│   ├── q2_most_product_sold_city.ipynb
│   ├── q3_best_time_to_advertise.ipynb
│   ├── q4_most_sold_together.ipynb
│   └── q5_most_sold_product.ipynb
├── .gitignore
└── README.md
```

## Requirements

- Python 3.6+
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Running the Analysis

1. First, run `data_cleanup.ipynb` to clean the raw data
2. Run `merge_dataset.ipynb` to combine monthly sales data
3. Run the analysis notebooks (q1-q5) to answer specific business questions

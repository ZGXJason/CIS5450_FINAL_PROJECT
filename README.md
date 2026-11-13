# E-Commerce Delivery Delay Risk Prediction

CIS5450 Final Group Project

## Project Objective
Predict delivery delay risk after payment approval and before shipment, and evaluate how risk scores can support proactive customer service prioritization.

## Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)


We currently use two datasets:
- `olist_orders_dataset.csv`: Order information, including timestamps, delivery dates, and order status.
- `olist_order_items_dataset.csv`: Order item information, including prices, freight costs, and seller IDs.

## Project Structure

```text
CIS5450-Olist-Project/
├── data/
│   ├── raw/
│   │   ├── olist_orders_dataset.csv
│   │   ├── olist_order_items_dataset.csv
│   │   └── olist_customers_dataset.csv
│   └── processed/
│       └── olist_cleaned.csv
├── images/
│   └── er_diagram.svg
├── notebooks/
│   └── 01_data_cleaning.ipynb
├── README.md
└── .gitignore
```

## Team
- Gexiang Zhang 
- Ziyi Zhai 
- Yimeng Yin
- Ziqi Shang
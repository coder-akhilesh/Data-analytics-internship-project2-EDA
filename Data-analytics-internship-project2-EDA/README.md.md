# Customer Dataset

## Overview
This dataset contains 1,000 customer records with 10 features.

## Features

### Numeric Features
- **customer_id**: Unique identifier (1001-2000)
- **age**: Age in years (18-80)
- **income**: Annual income in USD
- **purchase_amount**: Amount spent per transaction
- **purchase_frequency**: Total number of purchases
- **days_as_customer**: Customer tenure in days
- **satisfaction_score**: Rating from 1-5 stars

### Categorical Features
- **product_category**: Electronics, Fashion, Home, Sports, Books
- **region**: North, South, East, West
- **last_purchase_date**: Date of most recent purchase

## Data Quality
- Total Records: 1,000
- Missing Values: 3% in income, 2% in satisfaction_score
- No duplicate records
- Date Range: Last 365 days

## Data Generation
- Generated using Python with NumPy and Pandas
- Random distributions with realistic patterns
- Includes intentional missing values for practice

## Usage
Use this dataset for practicing EDA techniques
# Hotel Booking Data Analysis

## Project Overview

This project focuses on analyzing hotel booking data to uncover customer booking behavior, cancellation trends, revenue patterns, and profitability drivers. Using Python-based data analysis techniques, the project provides actionable business insights that can help hospitality businesses improve customer retention, optimize pricing strategies, reduce cancellations, and maximize profitability.

The analysis was conducted using Exploratory Data Analysis (EDA), statistical summaries, and data visualizations created in Jupyter Notebook.


## Business Problem

Hotel businesses often face challenges such as:

* High booking cancellation rates
* Inefficient channel performance
* Revenue leakage due to refunds and promotions
* Difficulty identifying profitable customer segments
* Fluctuating demand across seasons and property types

This project aims to identify the key factors influencing these challenges and provide data-driven recommendations.


## Objectives

* Analyze booking trends across different channels.
* Evaluate room type and property performance.
* Identify patterns in booking cancellations.
* Understand the impact of lead time and stay length on customer behavior.
* Assess profitability using revenue, cost, markup, cashback, and coupon data.
* Generate actionable business recommendations.


## Dataset Features

The dataset contains information related to:

* Customer Details
* Property Information
* Booking Dates
* Room Types
* Star Ratings
* Booking Channels
* Booking Value
* Cost Price
* Selling Price
* Markup
* Refund Status
* Refund Amount
* Cashback
* Coupon Usage
* Booking Status
* Stay Length
* Lead Time


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


## Analysis Performed

### Data Cleaning & Preparation

* Handled data type conversions
* Created derived features such as:

  * Stay Length
  * Lead Time
  * Profit

### Exploratory Data Analysis

* Booking Status Distribution
* Room Type Analysis
* Star Rating Analysis
* Booking Channel Analysis
* Monthly Booking Trends
* Booking Value Distribution

### Cancellation Analysis

* Cancellation Rate by Channel
* Cancellation Rate by Room Type
* Cancellation Rate by Star Rating
* Lead Time vs Cancellation
* Refund Analysis

### Profitability Analysis

* Profit by Booking Channel
* Revenue by Room Type
* Revenue by Property Rating
* Impact of Coupons and Cashback

### Correlation Analysis

* Relationship between:

  * Booking Value
  * Cost Price
  * Selling Price
  * Profit
  * Stay Length
  * Lead Time


## Key Insights

### Booking Trends

* Certain booking channels generate higher booking volumes and revenue.
* Premium room categories contribute significantly to overall profitability.
* Higher-rated properties tend to attract higher-value bookings.

### Cancellation Behavior

* Longer lead times are associated with higher cancellation rates.
* Cancellation patterns vary across channels and room categories.
* Refund amounts have a significant impact on realized revenue.

### Revenue & Profitability

* Premium room types generate higher average profits.
* Promotional strategies influence booking conversion and margins.
* Some channels outperform others in both revenue generation and profitability.


## Business Recommendations

### Reduce Cancellations

* Introduce tiered cancellation policies.
* Offer incentives for non-refundable bookings.
* Implement automated reminder systems.
* Use predictive analytics to identify high-risk cancellations.

### Improve Profitability

* Focus on high-performing booking channels.
* Optimize cashback and coupon strategies.
* Promote premium room categories.
* Monitor channel-level profitability regularly.

### Increase Customer Retention

* Launch loyalty and membership programs.
* Offer personalized promotions.
* Improve post-stay customer engagement.

### Optimize Pricing Strategy

* Implement dynamic pricing models.
* Adjust pricing based on seasonality and demand.
* Run targeted promotions during low-demand periods.


## Project Structure

```text
Hotel-Booking-Analysis/
│
├── data/
│   └── Hotel_bookings_final.csv
│
├── notebooks/
│   └── Hotel_Booking_Analysis.ipynb
│
├── reports/
│   ├── Summary_Report.pdf
│   └── Presentation.pptx
│
├── images/
│   ├── booking_channel_analysis.png
│   ├── cancellation_analysis.png
│   └── profitability_analysis.png
│
└── README.md
```


## Future Enhancements

* Build a cancellation prediction model using Machine Learning.
* Create an interactive Power BI dashboard.
* Implement customer segmentation analysis.
* Forecast future booking demand using time-series models.

# Amazon-Customer-Coupon


Coupon Acceptance Data Analysis

This repository contains an assignment for the ML class built using Python in a Google Colab environment. The project analyzes driving and demographic factors to evaluate what drives driver to accept various types of coupons (Bar, Coffee House, Carry Out, Restaurants).

Overview

When driving, coupons are offered to drivers based on various factors (weather, destination, time, accompanying passengers) and demographic details (age, gender, income).

The primary goals are:

    Data Cleaning & Preprocessing: Mount cloud storage, query missing attributes, correct typos, handle NaN values, and normalize features.

    Data Analysis: Identify distributions across demographic variables (age, gender, marital status) and behavioral/visitation habits (frequency of visiting coffee houses, bars, carry-out spots).

    Target Analysis: Measure overall acceptance rate (Coupon Used) across various types.

    Data Visualization: Produce clear visual reports using static (matplotlib, seaborn) and interactive (plotly) graphing libraries.

Dataset Summary

    Records / Rows: 12,684

    Features / Columns: 26

    Source File: /data/coupons.csv

Key Variables Analyzed:

    CouponUsed (formerly Y): Binary target variable (1 = Accepted, 0 = Rejected).

    passenger (renamed from passanger): Driver context (Alone, Friend(s), Partner, Kid(s)).

    destination: Driver travel context (No Urgent Place, Home, Work).

    coupon: Category of coupon offered (Coffee House, Restaurant(<20), Carry out & Take away, Bar, Restaurant(20-50)).

    weather & temperature: Environmental conditions (Sunny, Rainy, Snowy; temperatures 30°F, 55°F, 80°F).

    Behavioral Frequency Columns: Bar, CoffeeHouse, CarryAway, RestaurantLessThan20, Restaurant20To50 (tracking frequency of visits per month).

Dependencies

Ensure you have the following Python libraries installed before running the notebook:
install pandas numpy matplotlib seaborn plotly

Note: Google Colab comes pre-installed with all required packages except specific driver mounts.

Getting Started & Execution

    Upload Dataset: Place coupons.csv in your Google Drive under /MyDrive/Colab Notebooks/data/.

    Open Notebook: Open the .ipynb file in Google Colab or Jupyter Notebook.

    Mount Drive & Run: Run all notebook cells sequentially:
    Python

    from google.colab import drive
    drive.mount('/content/drive')

Workflow & Methodology

    Drive Connection & Loading:

        Mount Google Drive and load /data/coupons.csv into a Pandas DataFrame (masterdata).

    Data Cleaning & Standardization:

        Renamed target output Y → CouponUsed.

        Fixed typographical errors: passanger → passenger.

        Identified  missing data in car (12,576 missing records out of 12,684).

        Filled missing categorical entries in visit frequencies with 'never'.

     Visualizations:

        Visualized overall coupon acceptance breakdown via pie charts.

        Evaluated acceptance grouped by coupon types across age and gender distributions.

        Histogram distribution across ambient temperature readings.

    Sub-segment Analysis:

        Filtered dataset subsets specifically targeting driver responses to Bar coupons (n=2,017).

💡 Preliminary Insights

    Overall Acceptance Rate: ~56.8% of coupons offered were accepted (7,210 accepted vs. 5,474 rejected).

    Most Frequently Offered Coupons:

        Coffee House (3,996)

        Restaurant (<20) (2,786)

        Carry out & Take away (2,393)

    Weather Context: The overwhelming majority of driving observations occurred during Sunny weather (10,069 records) at 80°F (6,528 records).

 

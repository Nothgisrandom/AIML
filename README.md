
# Will the Customer Accept the Coupon?

## Overview
This project analyzes customer behavior to determine whether they will accept a coupon under different circumstances. It specifically looks at factors such as the frequency of restaurant visits, income levels, and age groups while providing insights through visualizations and analysis.

## Project Structure
- **Notebook (.ipynb)**: The primary analysis is conducted in the Jupyter Notebook file, which includes data exploration, filtering, visualizations, and acceptance rate calculations. These contain the core logic for data filtering and calculations.
- **README.md**: The current file provides an overview of the project, methodology, and approach to explore the relation between customer attributes and the probability of accepting the coupon.

## Methodology
The analysis investigates customer groups based on their income level, restaurant visit frequency, and other factors. We calculate the acceptance rates for different groups and present visualizations to help interpret the results. The goal is to understand which customer groups will most likely accept coupons.


## Visualizations
Several visualizations are included to explore:
- The distribution of customer income levels.
    ![Image]
- The frequency of restaurant visits.
  ![Image](https://github.com/Nothgisrandom/AIML/blob/main/restaurant_visits_distribution.png )
- Missing data and its impact on the analysis.
![Image](https://github.com/Nothgisrandom/AIML/blob/main/MissingData.png)

## Findings
- **Acceptance Rates**: 
- Overall bar coupon acceptance rate= 41.0 %
- Acceptance rate for drivers who go to a bar more than once a month and are over the age of 25= 70.0 %
- The acceptance rate for drivers who go to bars more than once a month, have no kid passengers, and have occupations other than farming, fishing, or forestry= 71.0%
- The acceptance rate for frequent restaurant visitors earning less than $50K: 39%
- Acceptance rate for drivers who go to cheap restaurants more than four times a month and income is less than 50K= 39.0%

## Summary:
To get the highest acceptance rate (about 70%) with bar coupons, you should send more coupons to customers with the following attributes:
1. go to a bar more than once a month and are over 25.
2. go to bars more than once a month, have no kid passengers, and have occupations other than farming, fishing, or forestry.

## Independent Exploration:
I explored the coffee house compounds. Here are my key findings:
1. The overall coffee coupon acceptance rate is 50.0 %.
2. The coffee coupon acceptance rate for single, unemployed females who are 21 years old is 59.0 %.
3. No clear trend or relation with income levels.
![Image](https://github.com/Nothgisrandom/AIML/blob/main/income_acceptance_rate_chart.png)

   

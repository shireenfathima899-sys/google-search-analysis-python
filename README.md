# Google Search Analysis: Electric Vehicles in India

## Project Overview

This project analyzes Google Trends data for the search term "Electric vehicle" in India. Python is used to clean the data, identify trends, compare annual averages, and investigate monthly search-interest patterns.

The goal is to turn search-interest data into evidence-based recommendations for marketing and content planning.

## Business Questions

* How has relative search interest changed over time?
* Which weeks recorded the highest and lowest interest?
* How did annual average interest change from 2022 to 2025?
* Does February consistently show higher interest than October?
* How could these findings inform marketing experiments?

## Tools and Technologies

* Python
* pandas
* Matplotlib
* Seaborn
* Google Trends
* Google Colab

## Key Findings

### 1. Annual Trend

Average search interest declined from 73.90 in 2022 to 60.04 in 2025, an approximately 18.75% decline in the normalized interest score.

### 2. Peak Interest

The highest observed weekly score was 100 for the week beginning March 6, 2022.

Thirteen of the top 20 weekly observations occurred in 2022.

### 3. Monthly Comparison

February had an overall average score of 74.3, compared with 62.5 for October.

February's average was higher in each full calendar year from 2022 to 2025. However, the gap narrowed from 27.44% in 2022 to 4.42% in 2025.

## Business Recommendations

* Investigate events and announcements around major search-interest peaks.
* Validate monthly patterns before planning seasonal campaigns.
* Test marketing campaigns and compare qualified leads, test-drive bookings, conversions, and acquisition costs.
* Combine search-interest data with vehicle registrations and sales before drawing conclusions about actual demand.

## Limitations

Google Trends provides normalized interest scores rather than absolute search volumes. Search interest does not directly measure purchases or prove why interest changed. Monthly patterns may also be affected by unusual events and changing search behavior.

## Data Source

Google Trends: https://trends.google.com/trends/

Search term: Electric vehicle
Geography: India
Period: Approximately five years

## Project Structure

* `Google_Search_Analysis.ipynb`: Analysis notebook
* `01_overall_trend.png`: Weekly trend chart
* `02_annual_comparison.png`: Annual average chart
* `03_monthly_comparison.png`: Monthly comparison chart
* `README.md`: Project documentation

## Conclusion

The analysis identifies a decline in annual average relative search interest from 2022 to 2025 and a recurring February-versus-October difference. These patterns can guide further investigation and marketing experiments, but business decisions should be validated against actual market and campaign performance data.

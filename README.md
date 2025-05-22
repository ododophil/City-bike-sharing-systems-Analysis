# City Bike Rental Demand Analysis

This repository contains the analysis of a city bike-sharing system's rental data, exploring the factors that influence rental demand. The project aims to provide insights and recommendations to optimize operations and improve user satisfaction.

## Project Overview

City bike-sharing systems are increasingly important for sustainable urban mobility. Understanding the usage patterns of these systems is crucial for maximizing their efficiency and financial returns. This analysis investigates an extensive dataset of bike rental transactions, incorporating relevant weather and contextual data such as seasonality and holidays.

The primary objectives of this project are to:

*   Explain why customers rent bikes.
*   Identify peak demand times.
*   Provide concrete recommendations for strategic planning of the business venture.

Based on quantitative analysis, the goal is to provide findings that allow the business to optimize customer satisfaction and operating efficiency in an urban transit market environment.

## Top Insights

Based on the analysis, the following key insights were identified:

1.  **Bike rentals are heavily influenced by time and social context.** Demand is highest on weekends and holidays, particularly during daylight hours, indicating that most users are motivated by leisure and recreation.
2.  **Weather significantly drives bike rental demand.** Rentals peak during moderate temperatures (roughly 15-25°C) and comfortable weather conditions, while poor weather leads to a sharp decrease in usage.
3.  **Dynamic, data-driven strategies can maximize profit and user satisfaction.** Predictive analytics using weather and temporal data can help optimize bike availability, target marketing, and plan maintenance.

## Data

The analysis uses a dataset containing hourly records of bike rentals, weather conditions, and calendar details. The dataset is included in the repository as `bikes_data.xlsx`.

The dataset includes the following key variables:

*   `RENTALS`: Number of bike rentals (target variable).
*   `Temperature`, `Humidity`, `Wind Speed`, `Visibility`, `Dew Point Temperature`, `UV Index`, `Rainfall`, `Snowfall`: Weather-related features.
*   `Hour`, `Day of Week`, `Month`, `Season`: Temporal features.
*   `Holiday`: Indicates if the day is a holiday.

## Analysis

The analysis includes the following steps:

1.  **Data Loading and Preparation:** Reading the data from the Excel file and performing initial data quality checks.
2.  **Descriptive Statistics:** Exploring the characteristics of both numerical and non-numerical variables.
3.  **Correlation Analysis:** Examining the linear relationships between bike rentals and weather variables using a heatmap.
4.  **Temporal Pattern Analysis:** Visualizing average bike rentals by hour and day of the week using a heatmap.
5.  **Impact of Temperature:** Investigating the relationship between temperature and bike rentals using a scatter plot with a regression line.
6.  **Seasonal and Holiday Effects:** Analyzing bike rentals by season and holiday using a boxplot.

## Conclusion and Recommendations

This analysis examined the drivers of bike rental demand, leveraging transaction data in conjunction with weather and contextual information. The investigation has identified robust patterns that offer significant opportunities for optimizing the bike sharing system.

The key findings demonstrate a clear influence of temporal, environmental, and social factors on rental behavior. Notably, peak demand is strongly correlated with leisure periods such as weekends and holidays, and is concentrated within daylight hours. Furthermore, weather conditions, particularly temperature, significantly impact ridership, with optimal rentals observed during moderate temperatures and reduced usage during adverse weather events like heavy rain or extreme cold. Seasonal variations and the presence of holidays are also powerful determinants of rental volume, reflecting increased outdoor activity and tourism during favorable periods.

These insights can provide a foundation for strategic operational and marketing decisions. By understanding these predictable patterns, the business can:

**1. Enhance Fleet Management:** Proactively allocate bikes to high-demand locations during anticipated peak times, maximizing availability and service efficiency.

**2. Refine Demand Forecasting:** Integrate weather and temporal data into predictive models to anticipate fluctuations in ridership, enabling more accurate planning.

**3. Develop Targeted Strategies:** Design marketing campaigns and pricing strategies that capitalize on high demand periods while potentially stimulating usage during off-peak times.

By aligning operational strategies with the evidence presented, the bike sharing system can enhance both operational efficiency and user satisfaction, contributing to the success and sustainability of the business.

## Getting Started

To run this analysis, you will need:

*   Python
*   Pandas library
*   Matplotlib library
*   Seaborn library

You can run the code in a Jupyter Notebook environment or a similar platform that supports Python notebooks, such as Google Colab.

## References

*   Fishman, E., Washington, S., & Haworth, N. (2013). Bike Share: A Synthesis of the Literature. *Transport Reviews*, 33(2), 148-165.
*   Ricci, M. (2015). Bike sharing: A review of evidence on impacts and processes of implementation and operation. *Research in Transportation Business & Management*, 15, 28-38.

# Instacart Customer Segmentation and Shopping Patterns Analysis

## Overview
This project explores customer purchasing patterns using Instacart transaction data. By analyzing customer segments and shopping behaviors, the project provides actionable insights that can inform targeted marketing strategies and improve customer retention.

### Project Motivation
Understanding customer behavior is essential in today’s data-driven market. With Instacart’s vast transaction data, this project leverages customer segmentation to reveal purchasing patterns, enabling targeted marketing strategies and improving customer retention. Insights from this analysis can help Instacart cater more effectively to diverse customer needs, enhancing satisfaction and driving revenue.

## Data Access

- **Raw Data**: The original data files used in this project are available on Google Drive due to file size limitations. You can access the raw data [here](https://drive.google.com/drive/folders/1QUs8gjBmcwagTgJWZtXtdwBuoGm_DRxy?usp=sharing).
  
- **Prepared Data**: The cleaned and formatted datasets used for analysis are included in this repository under the [`data/` folder](https://github.com/syk-hub/Instacart-Customer-Segmentation-Analysis/tree/main/data). These files were processed to facilitate customer segmentation and shopping pattern analysis.

## Data Preparation and Tools
Data cleaning, segmentation, and formatting were conducted in Python using Jupyter Notebook. You can view the full notebook with data preparation steps [here](https://github.com/syk-hub/Instacart-Customer-Segmentation-Analysis/blob/main/customer_segmentation_v2.ipynb).


## Dashboard
The interactive Tableau dashboard presents key insights from the analysis, allowing for exploration of customer segments and shopping trends. You can view the full interactive dashboard on Tableau Public [here](https://public.tableau.com/shared/N33HTB89X?:display_count=n&:origin=viz_share_link).

![Dashboard Preview](https://github.com/syk-hub/Instacart-Customer-Segmentation-Analysis/blob/main/Instacart%20Customer%20Segmentation%20and%20Shopping%20Patterns.png)


### Key Dashboard Components
1. **Customer Segmentation Overview**: Provides a visual breakdown of customer segments by Recency, Frequency, and Monetary (RFM) scores.
2. **Top Products by Segment**: Displays the most purchased products for each segment to inform targeted product recommendations.
3. **Weekly Order Trends**: Analyzes shopping patterns by day of the week, showing peak times for customer engagement.
4. **Heatmap of Orders by Day and Time**: Illustrates order activity across different times and days, offering insights into peak shopping periods.

## Marketing Recommendations
- **Targeted Weekend Promotions**: High-value customers prefer shopping on weekends. Weekend discounts could increase loyalty and engagement.
- **Cross-Sell Strategies**: Use product affinity data to suggest complementary items during peak hours.
- **Retention Tactics for At-Risk Customers**: Personalized offers and reminders can re-engage at-risk customers.

## Repository Contents
- **`data/` folder**: Contains the cleaned, processed datasets used for analysis.
- **`data_preparation.ipynb`**: Jupyter Notebook detailing the data cleaning and preparation process.
- **Tableau Dashboard**: Linked above, showcasing the interactive visualizations and insights.

### Future Work and Limitations
- **Data Gaps**: The dataset lacks transaction timestamps, limiting in-depth time-series analysis.
- **Advanced Modeling**: Future work could incorporate machine learning models for improved churn prediction and customer value forecasting.
- **Expanded Segmentation**: Including demographic or geographic data would enable more targeted marketing strategies.
- **Seasonal Trends**: A longer-term dataset would allow for seasonal trend analysis, enhancing inventory and promotion strategies.



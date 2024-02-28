
# Sumamry:

This project delves into analyzing the power consumption patterns of Tétouan city in Morocco, utilizing data from a public utility operator. With the aim of understanding energy usage and its influencing factors, various visualization techniques and the XGBoost algorithm for regression modeling were employed. The dataset comprises nine attributes, including time-series data collected over the span of a year, with no missing values. Key factors affecting power consumption, such as temperature, humidity, and wind speed, were explored alongside the power consumption across different zones within the city.

The methodology section outlines the use of Python programming language, leveraging libraries like Pandas for data manipulation and Plotly for visualization. XGBoost, known for its effectiveness in supervised learning tasks, was employed to build predictive models. Evaluation metrics such as R-squared, Mean Absolute Error (MAE), and Root Mean Square Error (RMSE) were utilized to assess model performance. The results indicated notable correlations between power consumption and variables like temperature, with Zone 1 demonstrating higher power usage compared to other zones.

Visual representations including correlation heatmaps, boxplots of power consumption by zone and time, and feature importance analysis provided insights into the dynamics of energy usage in Tétouan. Temperature emerged as a significant driver of power consumption, particularly in the evenings. The findings suggest a need for efficient energy management strategies amidst increasing urbanization and demand for electricity. Overall, the study underscores the importance of monitoring and analyzing power consumption patterns for informed decision-making and sustainable energy usage in urban environments.

# Results: 

The analysis revealed several key insights into the power consumption patterns of Tétouan city. Firstly, correlation analysis indicated varying degrees of correlation between different variables. Notably, Zone 1 and Zone 2 power consumption exhibited a strong positive correlation, while other variables like diffuse flows showed weaker correlations with power consumption.

Boxplots provided visualizations of power consumption across different zones and time periods. Zone 1 consistently exhibited higher power consumption compared to Zones 2 and 3. Moreover, quarterly analysis showcased fluctuations in power consumption throughout the year, with peak consumption typically observed in the summer months.

Temperature and humidity were identified as significant factors influencing power consumption. Boxplots illustrated how temperature tends to increase in the evenings, coinciding with higher power usage, while humidity tends to decrease during the same period.

Furthermore, the feature importance analysis using XGBoost highlighted the hour as the most influential feature in predicting power consumption. This underscores the importance of considering time-related factors in energy consumption modeling.

Overall, these results provide valuable insights into the dynamics of power consumption in Tétouan city, emphasizing the need for effective energy management strategies to address increasing urbanization and demand for electricity.


# AirBNB_DataAnalytics_Project
This project explores and visualizes the Airbnb listings dataset for New York City. It focuses on uncovering key insights about listings, pricing, availability, neighborhoods, and host activity using Python libraries such as Numpy, Pandas, Matplotlib, and Seaborn.

# Objective

This project focuses on exploring and understanding the Airbnb listings in New York City. The primary goals include:
Analyzing room types, pricing patterns, and availability across various neighborhoods.
Understanding host behavior and listing strategies.
Identifying price outliers that may skew the data.
Offering actionable recommendations for both guests and hosts based on insights derived from the dataset.

# Dataset Summary
The dataset comprises 20,765 records with 22 features, which include:
id: Listing identifier
name: Listing title
host_name: Host's name
neighborhood_group: Borough where the listing is located
latitude/longitude: Geographical location
price: Cost per night
room_type: Type of accommodation
reviews_per_month: Average monthly reviews
availability_365: Days available in a year

# Workflow and Methodology
# 1. Data Cleaning
Addressed missing values in key columns such as price, neighborhood, and beds.
Converted last_review into datetime format for temporal analysis.
Capped extremely high prices (above $1,000) to avoid distortion in visualizations and statistical analysis.
# 2. Exploratory Data Analysis (EDA)
Room Type Insights
Bar plots revealed that Entire home/apt is the most listed room type.
Neighborhood Analysis
Compared average prices across boroughs.
Manhattan emerged as the most expensive area.
Availability Trends
Heatmaps highlighted correlations among price, availability_365, number_of_reviews, and beds.
Price Distribution
Histogram analysis showed that most listings fall between $50 and $300 per night.
Host Analysis
Boxplots exposed hosts with multiple listings, suggesting a pattern of professional hosting.
Review Analysis
Pair plots helped identify the relationships between reviews, pricing, and availability.
# 3. Data Visualization
Used multiple visual tools to extract and communicate insights:
Histograms & Boxplots: To understand price spread and detect outliers.
Bar Charts: For categorical distributions (room types, neighborhood groups).
Pairplots & Heatmaps: For exploring correlations in numerical data.

# Key Insights
Manhattan commands the highest average price, followed by Brooklyn.
Entire homes/apartments dominate the market, although private rooms are more budget-friendly
Listings priced above $10,000 are clear outliers and require filtering for meaningful analysis.
Properties with high availability and consistent reviews often have competitive pricing and attract more guests.
A number of hosts operate multiple listings, indicating a shift toward commercial-style hosting.


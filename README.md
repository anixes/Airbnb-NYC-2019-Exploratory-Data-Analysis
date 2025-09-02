# Airbnb-NYC-2019-Exploratory-Data-Analysis
This project explores the Airbnb NYC 2019 dataset, performing Exploratory Data Analysis (EDA) to uncover insights about hosts, neighborhoods, pricing, availability, and reviews.
The analysis is structured around business-driven questions:

Which neighborhoods and boroughs dominate the Airbnb market?

What types of listings are most common?

How does price vary across location, room type, and reviews?

Are there outliers or unusual host behaviors (e.g., “superhosts” with 50+ listings)?

How do reviews and availability relate to listing popularity?

The enriched Jupyter Notebook includes guiding questions, visualizations, and detailed insights for each analysis step.

Key Analyses

🔹 Basic Understanding

Number of hosts and listings

Distribution of room types (Entire home, Private, Shared)

Price distribution (mean, median, skewness)

🔹 Geographic Analysis

Listings count by borough

Most expensive neighborhoods

Scatter plot of listings by latitude/longitude

🔹 Host & Business Questions

Top 10 hosts by number of listings

Average listings per host

“Superhosts” with unusually many listings

🔹 Pricing Insights

Average price by room type

Price variation across boroughs

Do reviews influence pricing?

Identifying extreme outliers (> $1000/night)

🔹 Reviews & Popularity

Listings with the most reviews

Neighborhoods with highest average reviews

Relationship between reviews and availability

🔹 Time-based Analysis

Distribution of last_review dates (seasonality, trends)

Pricing patterns for newer vs older listings

🔹 Advanced EDA (Optional)

Pivot table: average price by borough × room type

Correlations: availability, reviews per month, and price

Feature engineering: price_per_review metric

Tech Stack

Python 🐍

Libraries: pandas, numpy, matplotlib, seaborn

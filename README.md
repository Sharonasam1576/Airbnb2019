# Airbnb2019
Project Title:
Airbnb NYC 2019 Data Analysis

Project Description:
This project explores Airbnb listings in New York City for 2019, focusing on pricing, availability, and neighborhood distribution. Through data analysis and visualization, we aim to understand key trends that impact Airbnb rentals, such as room type preferences, price variations, and review counts.

Problem Statement:
The goal of this project is to analyze Airbnb listings in NYC to answer key business questions:

What are the most common room types and their distribution?
How do prices vary across different neighborhoods?
How does availability change by room type and location?
What insights can we gain from the number of reviews and listing popularity?
Business Context
Understanding Airbnb trends is essential for both hosts and guests. This analysis helps:

Hosts determine competitive pricing and availability strategies.
Guests find optimal locations for stays based on affordability and reviews.
Airbnb optimize its platform by identifying trends in listing performance.
Data Understanding
The dataset used is Airbnb NYC 2019, which includes:

Listings information (name, host, neighborhood, room type, price, etc.)
Availability of listings
Number of reviews per listing
Data Loading and Cleanup
Handled missing values in columns like name, host_name, last_review, and reviews_per_month.
Removed unnecessary columns such as id, last_review, and name.
Checked and removed duplicate entries.
Hypothesis and Assumptions
Listings with more reviews are more popular and likely more affordable.
Entire home/apartment listings have higher prices than shared rooms.
Neighborhood influences pricing and availability significantly.
High availability indicates listings are either unpopular or seasonal.
Key Visualizations & Analysis
The project includes the following key visualizations:
✅ Distribution of Room Types – Shows the popularity of each type.
✅ Price Distribution – Helps identify the most common pricing ranges.
✅ Room Type Price Comparison – Highlights price variations between room types.
✅ Listings Distribution by Neighborhood – Analyzes where most listings are located.
✅ Availability by Room Type – Displays how often different room types are available.

Additional Analyses:
Correlation matrix to find relationships between key variables.
Price trends across neighborhoods.
Impact of reviews on price and listing popularity.


Key Insights & Conclusion
Entire homes/apartments dominate the listings, but private rooms are also popular.
Prices are highest in Manhattan and lowest in The Bronx.
The number of reviews does not directly impact price.
Shared rooms have the highest availability, indicating lower demand.
Neighborhood significantly influences pricing.

Future Scope
Apply machine learning to predict Airbnb prices.
Perform time-series analysis for seasonal trends.
Expand analysis to other cities for comparison.

# Airbnb2019
1. Project Title
Airbnb NYC 2019 Data Analysis

2. Project Description
This project explores Airbnb listings in New York City for 2019, focusing on pricing, availability, and neighborhood distribution. Through data analysis and visualization, we aim to understand key trends that impact Airbnb rentals, such as room type preferences, price variations, and review counts.

3. Problem Statement
The goal of this project is to analyze Airbnb listings in NYC to answer key business questions:

What are the most common room types and their distribution?
How do prices vary across different neighborhoods?
How does availability change by room type and location?
What insights can we gain from the number of reviews and listing popularity?
4. Business Context
Understanding Airbnb trends is essential for both hosts and guests. This analysis helps:

Hosts determine competitive pricing and availability strategies.
Guests find optimal locations for stays based on affordability and reviews.
Airbnb optimize its platform by identifying trends in listing performance.
5. Data Understanding
The dataset used is Airbnb NYC 2019, which includes:

Listings information (name, host, neighborhood, room type, price, etc.)
Availability of listings
Number of reviews per listing
6. Data Loading and Cleanup
Handled missing values in columns like name, host_name, last_review, and reviews_per_month.
Removed unnecessary columns such as id, last_review, and name.
Checked and removed duplicate entries.
7. Hypothesis and Assumptions
Listings with more reviews are more popular and likely more affordable.
Entire home/apartment listings have higher prices than shared rooms.
Neighborhood influences pricing and availability significantly.
High availability indicates listings are either unpopular or seasonal.
8. Key Visualizations & Analysis
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
9. Statistical Analysis (if applicable)
If you performed statistical tests (like correlation analysis), summarize your findings here.

10. Key Insights & Conclusion
Entire homes/apartments dominate the listings, but private rooms are also popular.
Prices are highest in Manhattan and lowest in The Bronx.
The number of reviews does not directly impact price.
Shared rooms have the highest availability, indicating lower demand.
Neighborhood significantly influences pricing.
11. How to Run This Project
Install the required libraries:
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
Clone this repository:
bash
Copy
Edit
git clone https://github.com/yourusername/airbnb-nyc-analysis.git  
Run the Jupyter Notebook or Python script to generate visualizations.
12. Future Scope
Apply machine learning to predict Airbnb prices.
Perform time-series analysis for seasonal trends.
Expand analysis to other cities for comparison.

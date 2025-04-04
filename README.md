# Zomato Restaurants Expansion Analysis

## This analysis aims to identify potential areas for expansion, understand evolving market trends, and enhance restaurant partnerships.
### `Puja Chowdhury`
### `21/01/2025`

### Dashboad
![Screenshot 2025-02-20 at 3 44 18 PM](https://github.com/user-attachments/assets/82eccd4c-3613-4b8d-9df1-0268adf74820)

## Objective
The aim of this project is to analyze market trends, customer preferences, and restaurant performance to identify potential locations for Zomato’s restaurant expansion. Key goals include:

1. Identifying Expansion Areas – Pinpoint regions with growth opportunities.


2. Analyzing Market Trends – Understand customer spending, competition, and pricing strategies.


3. Optimizing Restaurant Portfolio – Improve customer engagement, enhance offerings, and boost market share.

## Data Acquisition
The dataset consists of 9551 restaurant entries across 15 countries and 141 cities, containing:

Location Data: CountryCode, City, Address, Longitude, Latitude.

Restaurant Features: Has_Table_booking, Has_Online_delivery.

Customer Feedback: Ratings, Votes.

Sources include Newton School Data, Business Insider (Currency rates), and Zomato’s database.

## Data Transformation
To ensure data quality, the following steps were performed:

Handling Missing Values: Filled missing cuisine types with the most common cuisine per country.

Standardizing Formats: Fixed spelling errors in city names and converted date formats.

Currency Standardization: Converted Average_Cost_for_Two to INR for consistency.

Enhancing Readability: Used XLOOKUP to replace CountryCode with full country names.

## Data Modeling & Analysis
Different analytical methods were applied:

1. Statistical Analysis:


Votes, Ratings, and Average_Cost_for_Two were analyzed to identify high-performing restaurants.

Used COUNTIFS and Pivot Tables to determine restaurant distribution across countries and pricing tiers.


2. Trend & Geospatial Analysis:


Identified cuisine preferences and demand in different regions.


3. Time-Series Analysis:


Measured yearly customer engagement trends based on vote counts.


4. Competitive & Market Analysis:


Found that Sri Lanka, Australia, and Canada have high ratings but low competition, making them ideal for expansion.

Examined the correlation between pricing and ratings, concluding that price increases have minimal impact on ratings.

## Data Visualization
A dashboard was built to showcase key insights using:

Filters & Slicers: Country-wise and year-wise restaurant performance.

Pie Charts: Impact of Online Delivery and Table Booking on ratings.

Bar Charts: Restaurant counts by price range and country.

## Key Insights
1. Market Potential:


Australia, Canada, Singapore, Sri Lanka – Strong growth potential due to high ratings, increasing urbanization, and rising middle-class demand.

Sri Lanka & Indonesia – Emerging markets with low competition but growing food culture.


2. Customer Preferences:


Customers prefer mid-range restaurants with online delivery options.

Fusion & local cuisines are trending in Australia, Canada, and Singapore.


3. Online Delivery & Table Booking Impact:


Restaurants with online delivery have higher ratings due to convenience.

Table booking is more valuable for premium restaurants in urban centers.

## Strategic Recommendations
Recommendation with Reasoning


Expand in Tier-2 Cities -- High growth potential, less competition.

Partner with Mid-Priced Restaurants -- Customers prefer affordability over luxury.

Strengthen Online Delivery Services -- Strong correlation with customer satisfaction and engagement.

Diversify Cuisine Offerings -- Cater to evolving food trends and regional preferences.

Improve Logistics in Smaller Cities -- Enhancing delivery networks ensures better customer experience.


## Conclusion
Zomato has significant opportunities in Sri Lanka, Singapore, Canada, and Australia. By leveraging customer preferences, pricing insights, and service optimization, Zomato can expand efficiently while maintaining a strong competitive edge.


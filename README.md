# airbnb-pricing-analysis
Airbnb pricing analysis using Python and Tableau to explore how room type, property size, guest capacity, bedrooms, property type, and location influence nightly prices.
## Interactive Dashboard
View the interactive dashboard on Tableau Public: https://public.tableau.com/app/profile/mithali.killekar/viz/AirBNB_17876552053020/Dashboard1?publish=yes

# Airbnb Pricing Analysis

## Project Overview

This project analyzes Airbnb listing data to understand how factors such as
room type, property size, guest capacity, bedrooms, property type, and
location are associated with nightly prices.

The goal was to identify meaningful pricing patterns and develop an
interactive Tableau dashboard that could support better pricing decisions.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Excel
- Tableau
- Jupyter Notebook

## Dataset

The final analysis contains:

- 3,382 Airbnb listings
- 48 locations
- ₹2,814 median nightly price
- 4.68 average star rating

Key variables analyzed include:

- Basic Night Price
- Room Type
- Property Type
- Property Size
- Person Capacity
- Bedrooms
- Location
- Star Rating

## Data Preparation

The dataset was cleaned and prepared before analysis by:

- Checking missing values
- Reviewing inconsistent categories
- Cleaning room and property type fields
- Examining price distributions
- Investigating potential outliers
- Creating analysis-ready features
- Validating important numerical fields

Median price was used for most pricing comparisons because unusually
expensive listings can significantly influence average prices.

## Dashboard

The Tableau dashboard provides an interactive overview of Airbnb pricing
patterns across different listing characteristics.

### KPIs

- Median Nightly Price: ₹2,814
- Total Listings: 3,382
- Average Rating: 4.68
- Total Locations: 48

### Dashboard Analysis

The dashboard explores:

- Median nightly price by room type
- Listings by property size
- Median nightly price by guest capacity
- Top property types by listing volume
- Top locations by listing volume
- Median nightly price by bedrooms

## Key Insights

### 1. Room Type Influences Pricing

Entire-home listings have a median nightly price of approximately ₹3,110,
compared with ₹2,104 for private rooms and ₹1,110 for shared rooms.

This indicates that guests generally pay a premium for privacy and exclusive
use of a property.

### 2. Guest Capacity and Price

Nightly prices generally increase as guest capacity increases.

Larger-capacity properties can command higher prices, although groups with
fewer listings should be interpreted carefully.

### 3. Property Size Distribution

Small and medium properties dominate the dataset:

- Small: 1,441 listings
- Medium: 1,428 listings
- Large: 586 listings

### 4. Bedrooms and Pricing

Median nightly prices generally increase with bedroom count, although the
relationship is not perfectly linear.

The final analysis focuses on 1–6 bedroom properties to reduce the influence
of very small sample groups.

### 5. Location Matters

Pricing varies significantly across locations.

Among the locations selected based on listing volume, Donaje and Pirangut
showed higher median nightly prices than Pune.

These results represent pricing differences and should not be interpreted
as those locations having more listings than Pune.

## Business Recommendations

- Compare properties with similar capacity, room type, bedrooms and location
  when establishing a base nightly price.
- Entire-home properties may support premium pricing compared with private
  or shared rooms.
- Larger-capacity properties can potentially command higher prices.
- Location should be incorporated into pricing decisions.
- Avoid drawing strong conclusions from premium categories with very few
  listings.
- Consider listing volume and sample size alongside median price.

## Conclusion

The analysis shows that Airbnb nightly pricing is associated with several
factors, including property characteristics, guest capacity, privacy and
location.

The project demonstrates an end-to-end analytics workflow involving data
cleaning, exploratory data analysis, validation, business interpretation
and Tableau dashboard development.

## Future Improvements

Future versions of the project could incorporate:

- Seasonal pricing
- Weekend vs weekday pricing
- Availability and demand
- Local events
- Competitor pricing
- Machine learning price prediction

These features could be used to extend the analysis into a more complete
dynamic pricing system.

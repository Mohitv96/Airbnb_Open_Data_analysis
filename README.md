# Seattle Airbnb Open Data Analysis
### Strategic Insights into Pricing, Neighborhoods, and Seasonal Trends

## 1. Project Overview
This project performs an Exploratory Data Analysis (EDA) on the Seattle Airbnb dataset. By analyzing thousands of listings, we aim to provide actionable insights for travelers looking for the best deals and hosts looking to optimize their pricing strategies.

**Key Research Questions:**
* How do prices fluctuate across different Seattle neighborhoods?
* What is the impact of seasonal demand on rental costs?
* What are the primary factors (amenities, location) that drive listing prices?## 2. Environment Setup & Data Acquisition


In this section, we initialize our environment with necessary libraries (Pandas, Seaborn, Matplotlib) and establish a relative file path to ensure the project remains portable for other users.

## 3. Data Preprocessing
Raw data often contains "noise" that prevents mathematical analysis. Here, we:
* **Currency Conversion:** Transform price strings (e.g., "$150.00") into numeric floats.
* **Missing Value Imputation:** Address null values in critical columns like `review_scores_rating`.
* **Feature Engineering:** Extract month and year data from timestamps to enable seasonal analysis.


## 4. Exploratory Data Analysis (EDA)

### 4.1 Neighborhood Price Distribution
*Goal: Identify which Seattle areas are the most premium versus budget-friendly.*

## 5. Final Conclusion & Key Takeaways
After analyzing the Seattle Airbnb market, we have reached the following conclusions:

1.  **Peak Season:** July and August represent the highest price points, suggesting a surge in summer tourism.
2.  **Location Premium:** Neighborhoods like **Downtown** and **Queen Anne** consistently command higher prices regardless of the season.
3.  **Data-Driven Hosting:** High review scores show a strong correlation with specific amenities listed in the descriptions, proving that host engagement directly impacts listing success.

---

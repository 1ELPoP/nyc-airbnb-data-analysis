# NYC Airbnb Market Analysis (Python & Power BI)

An end-to-end data analysis project exploring the New York City Airbnb market to uncover pricing patterns, stay-duration behavior, borough and neighborhood differences, and investment opportunities using **Python** and **Power BI**.

## Project Objectives
- **Market Dynamics:** Analyze supply, listing density, room types, and availability across NYC boroughs.
- **Data-Driven Pricing:** Help hosts and investors understand how location and property type affect nightly rates.
- **Tenant Behavior:** Examine how minimum-night requirements (`minimum_nights`) relate to pricing and listing distribution.

## Methodology & Pipeline
1. **Data Source:** New York City Airbnb dataset (approx. 50,000 listings).
2. **Data Preprocessing (Python):**
   - Inspected missing values, data types, and summary statistics.
   - Handled missing review fields (`reviews_per_month` imputed with `0` for listings with no reviews) and missing listing names (`"Unknown"`).
   - Treated extreme price anomalies using the Interquartile Range (IQR) method so average price metrics remain realistic.
   - Engineered `stay_category` from `minimum_nights` (e.g., Short-term, Weekly, Monthly, Long-term, Extreme Long-term).
3. **Interactive Dashboard (Power BI):**
   - Built a multi-page dashboard covering **Market Overview** and **Pricing Strategy & Booking Trends**.

## Key Insights & Recommendations
- **Location & Pricing:** Manhattan shows the highest average nightly rates, while Brooklyn offers strong listing volume and balanced mid-tier pricing.
- **Room Types:** Entire homes/apartments represent the largest share of listings and market demand.
- **Stay Duration:** Short-term stays account for the majority of listings, highlighting the role of minimum-stay flexibility.
- **Outlier Impact:** Addressing extreme price outliers with IQR prevents skewed averages in executive reporting.

## Project Files & Presentation
- **Python Notebook / Script:** Data cleaning, outlier handling, and feature engineering pipeline.
- **Power BI Dashboard (`.pbix`):** Interactive visual report.
- **Presentation (PDF):** [New-York-City-Airbnb-Market-Analysis.pdf](https://github.com/user-attachments/files/35327928/New-York-City-Airbnb-Market-Analysis.pdf)

## Contributors
- Omar Ahmed Abdulrahim
- Shahinaz Abdel Raouf Khalil
- Aya Montaser Ahmed
- Sarah Mohammed Rajeh
- **Supervised by:** Dr. Alshaimaa Hussien
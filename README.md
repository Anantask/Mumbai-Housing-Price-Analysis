Case Study : Mumbai Housing Price Analysis

Project Title
Mumbai Real Estate – Housing Price EDA & Dashboard

Project Objective
To analyse Mumbai housing data and uncover what drives property prices across different
locations, BHK types, and society categories. The goal was to help a potential buyer or
investor understand where to buy and what factors impact price the most.

Tools & Technologies Used
1. **Python (Pandas, NumPy)** – Data cleaning, feature engineering, aggregations
2. **Seaborn & Matplotlib** – EDA and visualizations
3. **Power BI** – Interactive dashboard for price trends and location comparisons

Data Overview
- 500 housing records across 20 Mumbai locations
- Key attributes: Location, BHK, Bath, Total Sqft, Price per Sqft, Price (Lakhs),
  Society Type, Availability

Analysis Performed

Univariate Analysis
- Price distribution is right skewed — majority of properties between ₹40–200L
- 2BHK and 3BHK are the most common property types
- Luxury outliers exist above ₹500L

Bivariate Analysis
- Clear positive correlation between sqft and price
- Location has a stronger impact on price than BHK count
- Bandra West, Juhu and Worli are the most expensive areas

Multivariate Analysis
- Correlation heatmap shows price_per_sqft as the strongest price predictor
- Pivot heatmap (Location × BHK) reveals pricing patterns across combinations
- Luxury society types command 2x the price per sqft vs affordable ones

Key Insights
- Location is the single biggest price driver in Mumbai real estate
- A 2BHK in Bandra West costs more than a 4BHK in Panvel
- Price distribution is heavily right skewed with clear luxury outliers
- Strong positive correlation between sqft and final price
- Society type (Luxury/Premium/Mid-Range) significantly affects pricing

 Business Outcomes
- Buyers can identify best value-for-money locations
- Investors can spot underpriced areas based on price per sqft
- Dashboard enables location-wise filtering for quick decision making

 What I Learned
- Feature engineering (price_per_sqft, is_expensive categories)
- Handling outliers in real estate data
- Building location-based comparative visualizations
- Translating housing data into buyer/investor insights

POWER BI DASHBOARD:



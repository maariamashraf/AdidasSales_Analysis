# Adidas U.S. Sales Analysis Project

## Overview
This project analyzes Adidas sales data in the U.S. to uncover patterns across products, retailers, and regions. The goal is to identify drivers of revenue and profitability, enabling better pricing, inventory allocation, and marketing strategies.

Ultimately, the goal is to translate raw sales data into actionable insights that support revenue growth and stronger competitive positioning in the U.S. market.

## Dataset
- **Time Period:** 2020-2021 Adidas sales transactions in the U.S.
- **Records:** 9,658 transactions
- **Attributes:** 17 variables including sales, demographics, and retailer data
- **Data Sources:** Sales transactions and demographic data from retailers

## Data Preprocessing
The dataset required cleaning to address:
- Duplicate records removal
- Missing value handling
- Data inaccuracies (e.g., negative values in sold units)
- Regional value standardization

## Methodology
**Analysis Approach:** Descriptive analysis and trend identification using Python libraries (pandas, numpy, matplotlib, plotly). Performed time-based sales trend analysis across monthly/quarterly periods and customer segmentation by age groups and regions.

**Techniques:**
- Time series aggregation for sales trends
- Demographic and geographic segmentation analysis
- Cross-tabulation to compare performance across customer segments
- Data visualization through charts and graphs to identify patterns and insights

Analysis focused on exploratory data analysis to uncover business insights from historical sales patterns.

## Key Findings
- **Product Performance:** Men's Streetwear and Footwear are top-performing categories with seasonal peaks in July and December
- **Customer Demographics:** Consumers under 40 drive majority of profits
- **Geographic Performance:** California, Texas, Florida, and New York generate highest revenues (tourism-driven markets)
- **Retail Channels:** Outlet stores outperform other channels, particularly in California and Texas
- **Partner Performance:** West Gear delivers highest operating profit and unit sales

## Strategic Recommendations
- Focus seasonal promotions on Men's Streetwear and Footwear during peak months
- Target marketing campaigns toward under-40 demographics
- Expand operations in high-performing tourism states
- Leverage Tennessee's 60% native customer adoption rate for localized growth
- Strengthen West Gear partnership and support Foot Locker's men's footwear sales
- Maximize outlet channel investment in California and Texas
- Implement balanced digital-physical channel strategy

## Technologies Used
- **Python:** pandas, numpy, matplotlib, seaborn, plotly
- **Analysis:** Exploratory Data Analysis (EDA)
- **Visualization:** Interactive charts, statistical plots, and trend analysis

## Files Structure
```
├── adidas_sales_analysis.ipynb    # Main analysis notebook
├── data/                          # Dataset files
├── reports/                       # Final presentation/report
└── README.md                      # This file
```

## Usage
1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Open and run `adidas_sales_analysis.ipynb`

## Future Work
- **Machine Learning Implementation:** Develop predictive models for sales forecasting, customer churn prediction, and demand planning
- **Advanced Analytics:** Customer lifetime value modeling and price optimization algorithms
- **Seasonal Forecasting:** Deep-dive seasonal trend analysis with predictive capabilities
- **Competitive Intelligence:** Market positioning analysis and competitor performance modeling
- **Real-time Analytics:** Dashboard development with automated insights and alerts

---
*This analysis provides a data-driven foundation for strategic decision-making in the U.S. Adidas market.*

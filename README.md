## Global Supply Chain & Order Analytics
This project presents an end-to-end exploratory data analysis (EDA) of a global supply chain orders dataset, enriched with GDP and population data from the World Bank. The goal is to understand *how operational, financial, and geographic factors influence sales performance, profitability, delivery delays, and market concentration*.

*The analysis is based on transactional data from a fictional global retail company (DataCo), commonly used for educational and analytical purposes, and simulates real-world order processing, shipping, and customer behavior across multiple regions and markets.

### Key Objectives
- Identify which order sizes, markets, and customer segments drive the most sales and profit
- Analyze delivery performance and determine the main factors influencing delays
- Explore seasonality patterns in order volumes
- Examine relationships between economic indicators (GDP per capita) and order activity
- Measure inequality and concentration of profits and orders across countries using Lorenz curves and Gini indices
- Determine product popularity trends overall and by customer segment
- Compare profit margins across markets, segments, and payment types

### Data Sources
**Orders dataset**: DataCo Supply Chain Dataset (fictional company, global scope)
**Economic data**: GDP and population indicators retrieved from the World Bank (wbdata API)

### Methods & Techniques implemented
- Data cleaning and preprocessing (outliers, missing values, normalization)
- Country name standardization and **ISO3** mapping for dataset merging
- Feature engineering (order size, delivery delay metrics, profit margins)
- Aggregation and group-level analysis
- Statistical analytics
  - Correlation analysis (Pearson & Spearman)
  - Inequality analysis using Lorenz curves and Gini coefficients
- Data visualization with **Matplotlib** and **Seaborn**

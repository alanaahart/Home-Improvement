## Forecasting Revenue & Financial Health in Home Improvement Retail

Interactive financial dashboard for home improvement retailers. Retrieves company data via Financial Modeling Prep, transforms it in Python, and visualizes key metrics in Tableau to assess financial health across major industry players. Includes time series revenue forecasts for Home Depot and Lowe’s over the next eight quarters using Prophet.

## [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alanaahart/Home-Improvement/blob/main/Home_Improvement_Analysis(1).ipynb)


## Tableau Dashboard

[View the interactive dashboard on Tableau Public](https://public.tableau.com/shared/FYYB7KMTQ?:display_count=n&:origin=viz_share_link)

## Tools & Methods 

### Python & Jupyter Notebook
- Used to connect to the **Financial Modeling Prep (FMP) API**
- Extracted financial data 
- Cleaned and transformed data using `pandas` for compatibility with Tableau
- Performed time series forecasting with Prophet for Home Depot and Lowe’s (8-quarter revenue projection)

### Financial Modeling Prep API
- Queried endpoints for:
  - Company financial statements
  - Key ratios (Current, Quick, Cash, Operating Cash Flow)
- Parsed JSON responses into structured dataframes
- Enabled dynamic data retrieval for multiple companies

### Tableau Public
 - Imported cleaned and forecasted data
 - Designed executive finance dashboard with:
     - KPI carousel for liquidity metrics
     - Company level filtering and interactivity
     - Revenue trend comparisons across companies
 - Published dashboard to Tableau Public for sharing

### Integration Workflow
1. **Extract**: Pull financial data from FMP API using Python
2. **Transform**: Clean and reshape data for analysis
3. **Forecast**: Forecast revenue using Prophet
4. **Load**: Export to CSV and import into Tableau
5. **Visualize**: Build interactive dashboard tailored for executive decision-making 

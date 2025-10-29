Interactive financial dashboard for home improvement retailers. Retrieves company data via Financial Modeling Prep, transforms it in Python, and visualizes key metrics in Tableau to assess financial health across major industry players.

## [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/REPO_NAME/blob/main/NOTEBOOK_NAME.ipynb)


## Tableau Dashboard

[View the interactive dashboard on Tableau Public](Home_Improvement_Analysis.ipynb)

## Tools & Methods 

### Python & Jupyter Notebook
- Used to connect to the **Financial Modeling Prep (FMP) API**
- Extracted financial data 
- Cleaned and transformed data using `pandas` for compatibility with Tableau

### Financial Modeling Prep API
- Queried endpoints for:
  - Company financial statements
  - Key ratios (Current, Quick, Cash, Operating Cash Flow)
- Parsed JSON responses into structured dataframes
- Enabled dynamic data retrieval for multiple companies

### Tableau Public
- Imported cleaned data for visualization
- Designed an **executive finance dashboard** featuring:
  - KPI carousel for liquidity metrics
  - Company level filtering and interactivity
- Published the dashboard to Tableau Public for public access and sharing

### Integration Workflow
1. **Extract**: Pull financial data from FMP API using Python
2. **Transform**: Clean and reshape data for analysis
3. **Load**: Export to CSV and import into Tableau
4. **Visualize**: Build interactive dashboard tailored for executive decision-making

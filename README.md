# Life Expectancy and GDP Analysis Project

## Overview
This project analyzes the relationship between a country's GDP and its life expectancy at birth. It involves data cleaning, exploratory data analysis, visualization, and statistical correlation assessments to uncover trends and insights over time.

## Objectives
- **Time Series Visualization:** Track the evolution of life expectancy and GDP over the years for multiple countries.
- **Correlation Exploration:** Examine how GDP and life expectancy correlate, including exploring potential lag effects.
- **Comparative Analysis:** Identify disparities and trends across different countries, highlighting outliers and significant changes.
- **Statistical Analysis:** Use regression models and Pearson correlation to quantify relationships between the variables.

## Data
- **Source:** Data is sourced from `all_data.csv`, which contains:
  - Country
  - Year
  - Life expectancy at birth (years)
  - GDP
- **Preprocessing:** The dataset undergoes column renaming (e.g., changing `Life expectancy at birth (years)` to `Life_expectancy`) and cleaning to ensure consistency for analysis.

## Analysis & Visualizations
- **Outlier Detection:** Box plots are used to detect anomalies in GDP and life expectancy.
- **Time Series Analysis:** 
  - Line plots and scatter plots present trends for individual countries.
  - Aggregate visualizations depict overall trends across all countries.
  - Lag effect analysis involves shifting GDP data to assess its impact on life expectancy.
- **Correlation Assessment:** Scatter plots and Pearson correlation coefficients help evaluate the strength of the relationship between GDP and life expectancy.
- **Advanced Visualizations:** Interactive charts and 3D plots are generated using Plotly for deeper exploratory analysis.

## Tools & Libraries
- **Programming Language:** Python
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Statsmodels
  - SciPy
  - Plotly

## Usage
1. **Setup Environment:**  
   Ensure all required libraries are installed. You can install them via pip:
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scipy plotly
   ```

2. **Run the Analysis:**
Open and execute the Jupyter Notebook (life_expectancy_gdp.ipynb) to:
- Load and preprocess the data.
- Generate time series visualizations and scatter plots.
- Compute statistical measures and display interactive visualizations.

3. **Review Results:**
The output charts and statistical analyses provide insights into how GDP influences life expectancy, supporting further research and policy decision-making.

## Article
Also, you can access my article about the resultes of the analysis in [The Link Between Economic Growth and Life Expectancy Insights from Data](https://medium.com/@olavodalberto921/the-link-between-economic-growth-and-life-expectancy-insights-from-data-1c01aae303ee).
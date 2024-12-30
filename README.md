# Economics and Education Analysis Project

This project explores the relationship between economic indicators (GDP, GDP per capita) and educational metrics across different countries and continents. The analysis covers data from 2021-2023 and examines correlations between educational factors and economic growth.

## Project Structure

The project consists of three main Jupyter notebooks:

1. `get_clean_data.ipynb`: Data collection and preprocessing
   - Scrapes GDP data from Wikipedia
   - Processes education data from Kaggle
   - Creates combined datasets for analysis

2. `run_analysis.ipynb`: Statistical analysis and modeling
   - Calculates summary statistics
   - Performs correlation analysis
   - Builds regression models
   - Analyzes GDP growth patterns

3. `visualize_results.ipynb`: Data visualization
   - Creates bar plots of continental growth
   - Generates pie charts of global GDP distribution
   - Produces scatter plots of education vs GDP relationships
   - Creates animations of GDP changes over time

## Dependencies

The following Python libraries are required:

- pandas
- numpy
- seaborn
- statsmodels
- requests
- beautifulsoup4
- matplotlib
- jupyter

## Key Findings

1. Global Economic Growth:
   - Average global GDP growth (2021-2023): 11.97%
   - Average per capita growth: 10.9%
   - Americas showed highest continental growth

2. Educational Correlations:
   - Birth rate, primary education enrollment, tertiary education enrollment, and youth literacy rates are statistically significant predictors of GDP per capita
   - Regression model explains 58.5% of GDP per capita variation
   - Strongest correlation between tertiary education enrollment and GDP per capita (0.52)

3. Global Distribution:
   - Asia: 36.3% of global GDP
   - Americas: 34.4%
   - Europe: 24.6%
   - Africa: 2.8%
   - Oceania: 1.9%

## Data Sources

- GDP Data: Wikipedia tables for nominal GDP and GDP per capita
- Education Data: Kaggle dataset containing educational metrics
- Combined Dataset: 167 countries with both economic and educational data

## Usage

1. Run `get_clean_data.ipynb` first to collect and prepare the datasets
2. Execute `run_analysis.ipynb` to perform statistical analysis
3. Use `visualize_results.ipynb` to generate visualizations

## Future Improvements

1. Data Collection:
   - Expand country coverage
   - Collect additional educational metrics
   - Include data from before 2021

2. Analysis:
   - Develop more complex regression models
   - Include interaction terms
   - Add second-order predictors
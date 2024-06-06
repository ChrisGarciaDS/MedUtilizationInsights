# Supply Chain Analysis

## Project Overview
This project focuses on analyzing the supply chain and inventory management within the cosmetics industry. The aim is to optimize inventory levels, reduce stockouts, and enhance supply chain efficiency.

## Data
The dataset used in this project contains information on cosmetics supply chain operations. It includes details on inventory levels, sales, and distribution across different regions.

## Repository Structure

- `data/`
  - `raw/`: Contains the original raw data file (`CosmeticsSupplyChainData.csv`).
  - `processed/`: Contains the cleaned and processed data file (`cleaned_CosmeticsSupplyChainData.csv`).

- `notebooks/`
  - `data_preparation.ipynb`: Jupyter notebook for data cleaning and preparation.
  - `data_analysis.ipynb`: Jupyter notebook for data analysis.
  - `visualizations.ipynb`: Jupyter notebook for creating visualizations.

- `scripts/`
  - `data_preparation.py`: Python script for data cleaning and preparation.
  - `data_analysis.py`: Python script for data analysis.
  - `create_visualizations.py`: Python script for creating visualizations.

- `results/`
  - `visualizations/`: Contains the generated visualizations (bar chart, line chart, scatter plot, map chart).

## Data Preparation
The data preparation process involves cleaning the dataset, handling missing values, and transforming the data for analysis. Missing numerical values are filled with the mean values based on similar product names, and categorical values are filled with the mode.

## Analysis
The analysis focuses on identifying key trends and patterns in the supply chain data. This includes examining inventory levels, sales trends, and distribution patterns across different regions.

## Visualizations
Key visualizations created during the analysis include:
- **Bar Chart**: Distribution of product sales by category.
- **Line Chart**: Trends in inventory levels over time.
- **Scatter Plot**: Relationship between sales and inventory levels.
- **Map Chart**: Geographic distribution of sales.

## Conclusion
This project provides insights into optimizing the supply chain and inventory management within the cosmetics industry. The findings can help improve decision-making processes and enhance overall supply chain efficiency.

## How to Use
1. Clone this repository.
2. Navigate to the `notebooks` directory to explore the Jupyter notebooks.
3. Run the scripts in the `scripts` directory to reproduce the analysis and visualizations.

## Contact
For any questions or feedback, please contact [Your Name] at [your.email@example.com].

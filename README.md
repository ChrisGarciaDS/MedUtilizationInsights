# Supply Chain Growth Analytics

## Project Overview (CURRENTLY BEING UPDATED)
This project focuses on analyzing the supply chain and inventory management within the cosmetics industry. The aim is to optimize inventory levels, reduce stockouts, and enhance supply chain efficiency. 

Data gathered from Kaggle: [data here]

## Data
The dataset used in this project contains information on cosmetics supply chain operations. It includes details on inventory levels, sales, and distribution across different regions.

## Repository Structure

- `data/`
  - `raw/`: Contains the original raw data file (`CosmeticsSupplyChainData.csv`). 
  - `processed/`: Contains the cleaned and processed data file (`cleaned_CosmeticsSupplyChainData.csv`).

- `notebooks/`
  - `data_preparation.ipynb`: Jupyter notebook for data cleaning and preparation. <DONE ON PYTHON>
  - [https://docs.google.com/spreadsheets/d/1g0E1_VtL36EMa5ikVqw4ulgV4DgW1E829xnp-2wXZs8/edit?usp=sharing]: Google Sheets for for data analysis.
  - [https://docs.google.com/presentation/d/1HWs2uye72BzV0D_Ju6Firci0l9gR4oUAxxt0xFA_J0w/edit?usp=sharing]: Presentation Slide Deck.

- `results/`: Contains the generated visualizations (bar charts)
  

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
3. Run the scripts in the `scripts` directory to reproduce the analysis and visualizations. <CHANGE THIS PART>

## Contact
For any questions or feedback, please contact Christopher at [cgarcia1@sandiego.edu].

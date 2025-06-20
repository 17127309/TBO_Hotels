# Hotel Dataset Exploratory Data Analysis

This project provides exploratory data analysis (EDA) and insights on a global hotel dataset, including focused analyses for Malaysia and Indonesia.

## Features

- Data cleaning and preprocessing
- Hotel rating normalization
- Visualizations:
  - Distributions of hotel ratings and other numeric features
  - Top cities and counties by number of hotels
  - Rating distributions by city and country
  - Correlation heatmaps
- Insights:
  - Top rated hotels globally and by country
  - Most popular cities/counties
  - Keyword analysis in hotel descriptions
  - Total and unique hotel counts (global and by country)
  - Handling of missing data

## How to Use

1. **Install dependencies**  
   Run in your terminal:
   ```
   pip install pandas matplotlib seaborn missingno
   ```

2. **Place your dataset**  
   Ensure your CSV file (e.g., `hotels.csv`) is in the project directory.

3. **Run the analysis**  
   - Use the provided Jupyter Notebook (`.ipynb`) for interactive exploration.
   - Or run the Python script (`.py`) for a full report in the terminal.

## Files

- `hotels_eda.ipynb` — Jupyter Notebook version
- `hotels.csv` — Example dataset (not included). You need to download from Kaggle link: https://www.kaggle.com/datasets/raj713335/tbo-hotels-dataset?resource=download
- `README.md` — Project overview and instructions

## Example Insights

- **Total number of hotels in the world:**  
  Shows both total records and unique hotel names.
- **Top 10 cities by number of hotels:**  
  Bar chart and table.
- **Top keywords in hotel descriptions:**  
  Most frequent words used in hotel descriptions.
- **Country-specific insights:**  
  Separate analyses for Malaysia and Indonesia.

## Customization

You can easily adapt the scripts to focus on other countries or add new insights by modifying the filtering and analysis sections.

## License

This project is for educational and
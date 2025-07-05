# Week2-Covid19-EDA
# COVID-19 Global Cases: Exploratory Data Analysis

This project presents a basic exploratory data analysis (EDA) on global COVID-19 case data using Python and data visualization libraries. The goal is to identify key trends, compare country-level impacts, and gain insights from the dataset.

## Dataset

- Source: [Kaggle - COVID-19 Dataset](https://www.kaggle.com/datasets)
- Columns Used:
  - `Date`
  - `Country`
  - `Confirmed`
  - `Recovered` *(simulated if not directly available)*
  - `Deaths`

##  Tools and Libraries

- Python
- Jupyter Notebook / Google Colab
- Libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`

##  Analysis Performed

- Data Cleaning:
  - Removed rows with null values in key columns
  - Renamed columns for clarity
- Summary Statistics:
  - Overview of cases, deaths, recoveries
  - Number of countries in dataset
- Visualizations:
  - Line chart: Global confirmed cases over time
  - Bar chart: Top 10 countries by total deaths
  - Pie chart: Global recovered vs deaths

##  Observations

- Some countries show significantly higher confirmed cases due to population or reporting practices.
- Recovery rates (simulated if missing) suggest a majority of patients recover.
- Death counts vary sharply by region.

##  How to Run

1. Download the dataset and place it in the same directory as the notebook.
2. Open the notebook `COVID19_EDA_Project.ipynb` in Jupyter or Google Colab.
3. Run all cells from top to bottom.

##  Requirements

```bash
pip install pandas matplotlib seaborn numpy

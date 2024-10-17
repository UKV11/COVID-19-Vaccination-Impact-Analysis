# COVID-19 Vaccination Impact Analysis

## Project Overview
This project aims to analyze how changes in COVID-19 vaccination rates correlate with the number of new cases and deaths among different countries in 2022. The analysis provides insights into the effectiveness of vaccination campaigns across various regions.

## Dataset
The dataset used in this project is sourced from [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv). It contains information about COVID-19 cases, deaths, and vaccination rates globally.

## Research Questions
1. How do changes in COVID-19 vaccination rates relate to new cases in 2022?
2. How do changes in vaccination rates affect the number of deaths due to COVID-19?

## Methodology
 **Regression Analysis**: To assess the relationship between vaccination rates, new cases, and deaths.
 **Time-Series Analysis**: To detect trends, seasonality, and residual effects of vaccination campaigns.

### Key Steps
1. **Data Preprocessing**: Cleaning and formatting the data, handling missing values.
2. **Exploratory Data Analysis (EDA)**: Generating descriptive statistics, visualizations (scatter plots, histograms).
3. **Regression Models**: Building and evaluating linear regression models to find correlations.
4. **Time-Series Models**: Applying ARIMA models to identify patterns over time.

## Results
The analysis reveals that vaccination rates have a significant impact on reducing new COVID-19 cases and deaths across multiple countries. Countries with higher vaccination rates experienced fewer new cases and deaths in 2022.

## Visualizations
This project includes:
 Histograms to represent vaccination rates and their effects.
 Scatter plots showing correlations between vaccination density and changes in cases and deaths.
 Time-series plots showing the trends over time.

## Conclusion
The findings suggest that higher vaccination rates are associated with a decline in new cases and deaths, contributing to the global fight against COVID-19. These insights can help in planning more effective public health policies.

## How to Run This Project
1. Clone this repository.
2. Install necessary Python libraries (requirements.txt is provided).
3. Open and run the Jupyter notebook `Covid 19.ipynb`.

## Technologies Used
 Python (Pandas, NumPy, Scikit-learn, Statsmodels)
 Jupyter Notebook
 Data visualization (Matplotlib, Seaborn)

# TASK 1- Gender-wise Population Analysis

This project analyzes gender-wise population statistics using CSV datasets (`female.csv`, `male.csv`, and `total.csv`). The goal is to clean, preprocess, and visualize global population trends for males and females over time.

---

## Tech Stack & Libraries

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib

---

## Files Used

-  Source: [World Bank - Total Population (SP.POP.TOTL)](https://data.worldbank.org/indicator/SP.POP.TOTL)
- `female.csv`: Contains percentage of female population data
- `male.csv`: Contains absolute male population data
- `total.csv`: Contains total population data
- Description - This dataset includes total population figures for all countries from 1960 to 2024.
---

## Features

- Reads and cleans raw CSV files
- Drops unnecessary columns like `Indicator Name` and `Indicator Code`
- Visualizes gender-wise population trends using Seaborn and Matplotlib
- Sets up consistent visual themes for plots

---

## Insights

-  **Log-Scaled Population Distributions** were used to better represent data with large disparities between countries.
-  **Male and female population histograms** showed a similar shape but had slight variations, suggesting overall consistency in gender proportions with a few regional exceptions.
-  **Total population (2024)** plot showed a right-skewed distribution where most countries have small populations and only a few (e.g., India, China) dominate the upper range.
-  **KDE curves** enhanced interpretability by smoothing the distributions and revealing natural clusters within the data.

---

##  How to Run

1. Clone this repository or download the notebook and data files.
2. Ensure you have all required libraries installed:

   ```bash
   pip install pandas matplotlib seaborn numpy

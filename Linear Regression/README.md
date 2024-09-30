# Linear Regression

## Overview
This repository contains my learning materials and practical implementations of Linear Regression using Python, specifically within Jupyter Notebook. The goal is to understand the fundamentals of Linear Regression and apply them to real-world datasets.

## Contents
- **Jupyter Notebooks**
  - `1_area_price.ipynb`: A notebook demonstrating Linear Regression analysis on housing prices based on area.
  - `p1_canada_capita_income.ipynb`: A notebook demonstrating Linear Regression analysis on canada capita income based on year.
  
- **Datasets**
  - `homeprices.csv`: Contains data related to home prices.
  - `areas.csv`: Contains data related to different areas.
  - `canada_per_capita_income.csv`: Contains data related to canada capita income on year bases.

- **Output Files**
  - `areas_predicted_price.csv`: Contains the predicted prices for the areas based on the Linear Regression model.

## Getting Started

### Prerequisites
To run the notebooks, you will need:
- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Running the Notebooks
1. Clone this repository or download the files.
2. Navigate to the directory containing the notebooks.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `1_area_price.ipynb` and follow along with the code.

## Learning Objectives
- Understand the concept of Linear Regression.
- Learn how to preprocess data for analysis.
- Implement Linear Regression using `scikit-learn`.
- Visualize results using `matplotlib`.

### Steps to teaching model
- Reading raw data from CSV File
- Create a scatter chart for the visual understanding
- Drop prediction column (In this case price column)
- Create `LinearRegression()` model
- Fit the dropped data and prediction column data (area and price)
- Predict the data using `model.predict([[]])` function
- Check Slope and Intercept
- Reading data prediction file.
- Predict the data (price data)
- Combine raw and predict data
- Create CSV file for that

## What I Learned and How I Completed the Task

### Key Learnings
- **Data Preprocessing**: I learned how to load a dataset using pandas, rename columns for easier access, and visualize relationships between variables using scatter plots.
- **Model Training**: I understood how to create a linear regression model using scikit-learn, fit it with training data, and make predictions for future values.
- **Visualization**: I gained experience in visualizing data trends, which helps in understanding how different factors influence outcomes.

### Steps Taken
1. **Data Loading**: I loaded the dataset containing Canada's per capita income data using pandas.
2. **Column Renaming**: To simplify access, I renamed the column 'per capita income (US$)' to 'income'.
3. **Data Visualization**: I created a scatter plot to visualize the relationship between years and per capita income, which helped me understand trends in the data.
4. **Model Creation**: I prepared my features by dropping the income column and trained a linear regression model with the remaining data.
5. **Making Predictions**: Finally, I used the model to predict Canada’s per capita income for the year 2020.
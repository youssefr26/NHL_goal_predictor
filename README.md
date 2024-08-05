# NHL_goal_predictor

## Overview

The Puck Predictor project aims to predict hockey player performance based on historical data. This project uses linear regression to forecast goals scored by players in the current season, leveraging features from previous seasons.

## Data Source

The data used for this project is obtained from [MoneyPuck](https://moneypuck.com/data.htm). The dataset includes various performance metrics for hockey players, including on-ice statistics, game scores, and more.

## Project Structure

1. **Importing Libraries:** Essential libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn` are imported for data manipulation, visualization, and modeling.

2. **Data Preparation:**

   - **Project Directory Setup:** Specifies the directory where the data is stored.
   - **Season Filtering:** Extracts and sorts data based on the seasons of interest.
   - **Data Loading:** Reads CSV files from the specified directories and combines them into a single DataFrame.
   - **Feature Selection:** Filters out necessary features for analysis and merges current and previous season data.

3. **Data Analysis:**

   - **Visualization:** Plots linear regression graphs to show correlations between features and goals scored.
   - **Modeling:** Trains a linear regression model using features from previous seasons to predict goals in the current season.

4. **Evaluation:**
   - **Model Performance:** Evaluates the model using RMSE and R² metrics.
   - **Prediction Visualization:** Plots predictions against actual values for the test season (2023).

## Usage

1. **Install Required Libraries:**

   Ensure you have the following libraries installed:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

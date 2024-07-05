# Predictive Modeling of Median House Values in California Using 1990 U.S. Census Data

conducted by Mitul Galav

![California Flag](https://upload.wikimedia.org/wikipedia/commons/6/65/Flag_of_California.png)

## Problem Statement

### Background

The dataset in question is derived from the 1990 U.S. Census, focusing on block groups, which are the smallest geographical units for which sample data is published. Each block group typically has a population ranging from 600 to 3,000 people. The dataset includes various demographic and housing attributes per block group, which are used to capture the socio-economic and housing characteristics of each area.

### Objective

The objective is to build a predictive model that accurately estimates the median house value (`median_house_value`) of block groups in California. The target variable, `median_house_value`, is expressed in hundreds of thousands of dollars ($100,000). By leveraging the independent variables provided in the dataset, we aim to understand the factors that significantly influence house values and develop a model that can predict these values for new or unseen data.

## Project Overview

### Goal

To develop a model that predicts the median house value (`median_house_value`) in California block groups based on the provided demographic and housing characteristics. The model should be capable of capturing the underlying relationships between the independent variables and the target variable, allowing for accurate predictions. This involves:

1. **Data Exploration and Preprocessing**: Understanding the distribution and relationships of the variables, handling missing values, and performing any necessary data transformations.
2. **Model Selection and Training**: Choosing appropriate machine learning algorithms and training models using the independent variables to predict the target variable.
3. **Model Evaluation**: Assessing the performance of the models using appropriate metrics and validating the results to ensure robustness.
4. **Prediction and Interpretation**: Using the trained model to make predictions on new data and interpreting the results to provide insights into the factors influencing house values in California.

### Expected Outcome

A reliable predictive model that can accurately estimate median house values in California block groups, providing valuable insights for real estate professionals, urban planners, and policymakers. This model can be used to identify trends, make informed decisions, and potentially guide future developments in the housing market.

## Python Libraries

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Data Loading

The dataset is loaded and preprocessed to handle missing values, categorical variables, and normalization as needed.

## Data Exploration

The data exploration phase involves understanding the dataset's structure, visualizing relationships, and identifying key patterns that may influence the target variable.

## Model Development

Various machine learning algorithms are employed to develop a predictive model, and their performance is evaluated using appropriate metrics such as Mean Absolute Error (MAE) and R-squared (R²).

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebook to see the analysis and model development steps.

## Results

The final predictive model will be presented along with its performance metrics, insights derived from the data analysis, and recommendations for future applications and improvements.

## Conclusion

This project demonstrates the potential of using census data to predict and analyze housing market trends, ultimately contributing to more informed decision-making in urban planning and real estate development.

## Author

Mitul Galav

---

For more details, refer to the Jupyter notebook in this repository.

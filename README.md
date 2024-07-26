# Forest-Fire-Prediction

This repository contains a Jupyter Notebook that performs predictive analysis on a dataset related to forest fires. The project involves data preprocessing, exploratory data analysis, feature selection, and model building to predict the likelihood of forest fires based on various environmental and geographical factors.

## Overview

The primary objective of this project is to develop a machine learning model that can predict forest fire occurrences. The dataset includes various features such as elevation, aspect, slope, and distances to water bodies, roads, and fire points. The target variable is the type of forest cover, which indicates the likelihood of a forest fire.

## Dataset

The dataset used for this analysis is sourced from a CSV file named `Forest Fire Prediction dataset.csv`. It contains multiple columns, including:

- `Elevation`
- `Aspect`
- `Slope`
- `Horizontal_Distance_To_Hydrology`
- `Vertical_Distance_To_Hydrology`
- `Horizontal_Distance_To_Roadways`
- `Hillshade_9am`
- `Hillshade_Noon`
- `Hillshade_3pm`
- `Horizontal_Distance_To_Fire_Points`
- `Cover_Type` (target variable)

## Methodology

1. **Data Loading and Exploration:**
   - Loading the dataset and understanding its structure.
   - Checking for missing values and basic statistical summary.

2. **Data Visualization:**
   - Visualizing the distribution of features and the target variable using histograms and count plots.
   - Exploring the relationships between features using box plots and correlation matrices.

3. **Feature Selection:**
   - Using an ExtraTreesClassifier to select the most important features.
   - Reducing the number of features based on their importance.

4. **Model Building:**
   - Splitting the data into training and testing sets.
   - Building a RandomForestClassifier to predict the `Cover_Type`.
   - Evaluating the model's performance using metrics like confusion matrix.

## Tools and Libraries

The analysis was conducted using the following tools and libraries:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results

The model successfully predicts the forest cover type, which helps in assessing the likelihood of forest fires. The results include accuracy scores and confusion matrices, providing insights into the model's performance.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please submit a pull request or open an issue.

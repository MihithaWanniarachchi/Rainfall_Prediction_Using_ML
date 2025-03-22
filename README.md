# Rainfall Prediction Using Random Forest

## Overview
This project focuses on predicting rainfall using the Random Forest machine learning algorithm. The dataset used consists of weather-related features, and the model is trained to determine whether it will rain the next day based on historical data.

## Features
- **Data Preprocessing**: Handling missing values, feature selection, and data transformation.
- **Exploratory Data Analysis (EDA)**: Understanding dataset distributions and correlations.
- **Model Implementation**: Using the Random Forest algorithm for classification.
- **Evaluation**: Assessing model performance using accuracy, precision, recall, and F1-score.

## Installation & Requirements
To run this project, you need to install the required Python libraries. Install them using the following command:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Usage
1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook "Rainfall Prediction Using Random Forest.ipynb"
   ```
2. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## Dataset
The dataset consists of multiple weather-related attributes such as temperature, humidity, wind speed, and pressure. Ensure that you have the dataset properly loaded before executing the notebook.

## Model Details
- **Algorithm**: Random Forest Classifier
- **Hyperparameters**: Tuned using GridSearchCV
- **Performance Metrics**: Accuracy, Precision, Recall, and F1-score

## Results
The model is evaluated using a test dataset, and the results are visualized using plots. Performance metrics highlight the model's effectiveness in predicting rainfall.

## License
This project is licensed under the MIT License.


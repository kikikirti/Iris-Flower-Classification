# Iris Flower Classification

## Project Overview

This project uses machine learning techniques to classify Iris flowers into three species: Setosa, Versicolor, and Virginica based on their sepal and petal measurements.

## Data Source

The data was obtained from the [Iris Flower Dataset on Kaggle](https://www.kaggle.com/datasets/arshid/iris-flower-dataset).

## Data Exploration

The dataset consists of 150 samples of Iris flowers, each described by four numerical features and one categorical target variable. Here's a summary of the features:

- **Sepal Length**: Length of the sepal in centimeters (float).
- **Sepal Width**: Width of the sepal in centimeters (float).
- **Petal Length**: Length of the petal in centimeters (float).
- **Petal Width**: Width of the petal in centimeters (float).
- **Species**: The species of the Iris flower (Setosa, Versicolor, Virginica) (categorical).

All 150 samples are complete with no missing values, ensuring a clean dataset for model training.

## Model Training

Three machine learning models were employed to classify the Iris flower species:

1. **Logistic Regression**: A linear model that estimates the probability of a categorical outcome based on the input features.
2. **Random Forest Classifier**: An ensemble model that combines multiple decision trees to improve classification accuracy.
3. **K-Nearest Neighbors (KNN) Classifier**: A non-parametric method that classifies samples based on the closest training examples in the feature space.

## Evaluation

The performance of each model was evaluated primarily using accuracy.

## Further Exploration

To enhance the project, the following steps could be undertaken:

- **Feature Engineering**: Creating new features from the existing ones to potentially improve model performance.
- **Model Hyperparameter Tuning**: Adjusting the hyperparameters of the models to achieve better accuracy.
- **Feature Importance Analysis**: Identifying which features have the most significant impact on the classification results.

## Acknowledgements

This project uses the Iris dataset, which is publicly available from the UCI Machine Learning Repository. Special thanks to Ronald Fisher and Edgar Anderson for collecting and introducing this dataset.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.



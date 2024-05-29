# Salary-estimation-using-K-nearest-Neighbor

---

# Salary Estimation Using K-Nearest Neighbors

This repository contains a project focused on estimating salaries based on various features using the K-Nearest Neighbors (KNN) algorithm. The project demonstrates data preprocessing, exploratory data analysis (EDA), model training, and evaluation processes.

## Project Overview

The objective of this project is to estimate an individual's salary based on specific features such as age, education level, capital gain, and hours worked per week. The KNN algorithm is employed to predict salaries, leveraging its simplicity and effectiveness for regression tasks.

## Dataset

The dataset used in this project contains the following features:
- age: The age of the individual.
- education.num: The number of years of education.
- capital.gain: Capital gains recorded.
- hours.per.week: The number of hours worked per week.
- income: The target variable representing the salary category, encoded as 0 (<=50K) and 1 (>50K).

## Project Structure

The project is organized into the following sections:

1. Data Loading and Preprocessing: Loading the dataset and preprocessing it to handle missing values, encoding categorical features, and feature scaling.
2. Exploratory Data Analysis (EDA): Analyzing the data distribution, visualizing relationships, and identifying patterns.
3. Model Training: Splitting the data into training and testing sets, and training the K-Nearest Neighbors regressor.
4. Model Evaluation: Evaluating the model's performance using metrics such as Mean Squared Error (MSE), R-squared (R²), and Mean Absolute Error (MAE).
5. Visualization: Visualizing the model's predictions and comparing them with actual values.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Model Evaluation Metrics

- Mean Squared Error (MSE): Measures the average of the squares of the errors.
- R-squared (R²): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.
- Mean Absolute Error (MAE): Measures the average magnitude of the errors in a set of predictions, without considering their direction.

## Results

The KNN model's performance is evaluated, and results are documented in terms of MSE, R², and MAE. Visualizations are provided to compare the predicted salaries with the actual values.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any improvements, suggestions, or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


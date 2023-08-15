# Wine Quality Prediction ML Model

This repository contains the code and resources for a Wine Quality Prediction Machine Learning Model. The purpose of this project is to develop a predictive model that can estimate the quality of wine based on a set of features. The model is built using Python and the scikit-learn library, and synthetic data is used to simulate the wine quality dataset.

# Introduction

Predicting the quality of wine is a common problem in the field of machine learning and data analysis. Wineries and experts often assess wine quality based on various chemical and sensory properties. This project aims to demonstrate the creation of a predictive model that estimates wine quality using a simple linear regression approach.

# Data Generation

In order to develop and showcase the predictive model, synthetic wine quality data is generated. The dataset consists of 1000 samples, each with 10 randomly generated features. The features are simulated using the np.random.rand() function from the NumPy library, which generates random values between 0 and 1. Coefficients are defined for each feature to establish a linear relationship between the features and the target variable. To mimic real-world scenarios, random noise is added to the target variable to make it more realistic.

# Model Building

The core of this project is the construction of a Linear Regression model. Linear regression is a simple machine learning algorithm that assumes a linear relationship between the input features and the target variable. The scikit-learn library provides a convenient implementation of Linear Regression. The model is trained on the synthetic wine quality dataset using the training subset of the data.

# Evaluation

To assess the model's performance, two evaluation metrics are used:

1) Mean Squared Error (MSE): This metric quantifies the average squared difference between the predicted wine quality and the actual wine quality in the test dataset. A lower MSE indicates better model performance.

2) R-squared (R2) Score: This metric measures the proportion of the variance in the target variable that can be explained by the model. It ranges from 0 to 1, where a higher R2 score indicates a better fit.

# Usage

To run and experiment with the Wine Quality Prediction ML Model, follow these steps:

1) Clone the repository:

   git clone https://github.com/your-username/wine-quality-prediction.git

2) Navigate to the project directory:

   cd wine-quality-prediction

3) Install the required dependencies. You can create a virtual environment to manage dependencies:

   pip install -r requirements.txt

4) Run the wine_quality_prediction.py script:

   python wine_quality_prediction.py

5) The script will train the model on the synthetic data, make predictions, and display the calculated MSE and R-squared score.

# Dependencies

The following dependencies are required to run the Wine Quality Prediction ML Model:

1) Python 3.6+
2) NumPy
3) pandas
4) scikit-learn

You can install the required packages using the following command:

pip install -r requirements.txt

# Contribution

Feel free to contribute to this project by creating issues or pull requests. Your feedback and contributions are highly appreciated!

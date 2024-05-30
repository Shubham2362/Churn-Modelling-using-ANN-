
# Churn Modelling using Artificial Neural Network (ANN)

This project focuses on building a Churn Prediction Model using an Artificial Neural Network (ANN) in Google Colab. The dataset used is based on customer churn data, and the model aims to predict whether a customer will churn or not.

### Table of Contents
 
- Introduction

- Dataset

- Dependencies

- Setup and Installation

- Running the Model

- Results

- Contributing

## Introduction

Churn prediction is a critical aspect of customer relationship management. This project uses an Artificial Neural Network (ANN) to build a predictive model for customer churn. The model is trained on a dataset containing various customer attributes and whether they have churned or not.

## Dataset

The dataset used for this project contains the following features:

1.RowNumber	

2.CustomerId

3.Surname

4.Customer ID

5.Credit Score

6.Geography

7.Gender

8.Age

9.Tenure

10.Balance

11.Number of Products

12.Has Credit Card

13.Is Active Member

14.Estimated Salary

15.Exited (target variable)

## Dependencies

The project requires the following libraries:

- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Setup and Installation
 
1.Clone the Repository:

2.Install Dependencies:

You can install the required dependencies using pip.

3.Open the Google Colab Notebook:

Upload the ANN_Churn_Model.ipynb notebook to your Google Drive and open it with Google Colab.

## Running the Model
*Load the Data:*

Ensure the dataset (churn_data.csv) is available in the correct directory.

*Preprocess the Data:*

Follow the steps in the notebook to preprocess the data. This includes encoding categorical variables, scaling features, and splitting the data into training and test sets.

*Build the ANN:*

The notebook includes steps to define the ANN architecture using Keras.

*Train the Model:*

Train the ANN on the training data. The notebook provides the code to compile and fit the model.

*Evaluate the Model:*

After training, evaluate the model's performance on the test set.

## Results

The results section in the notebook includes metrics such as accuracy, precision, recall, and F1-score. Visualizations of the training process and confusion matrix are also provided.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

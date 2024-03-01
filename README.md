# Loan Approval Prediction
This Python script predicts whether a loan will be approved or not based on various features in the dataset.
## Table of Contents
- Introduction
- Dependencies
- Dataset
- Usage
- Models
- Results
- Contributing
- License
## Introduction
This project aims to analyze a dataset containing information about loan applicants and predict whether a loan application will be approved or not. The prediction is based on features such as gender, marital status, education, employment status, and property area
## Dependencies
The project utilizes the following Python libraries:

- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
 Make sure you have these libraries installed in your Python environment.
## Dataset
The dataset used for this project is located in the file **train_u6lujuX_CVtuZ9i.csv**. It contains various attributes of loan applicants such as gender, marital status, education, income, loan amount, loan term, credit history, and property area.

## Usage
1. Clone the repository to your local machine:
   **git clone <repository-url>**
2. Navigate to the project directory:
   **cd Loan_Approval_Prediction**
3. Run the Python script loan_approval_prediction.py:
   **python loan_approval_prediction.py**
- The script will perform data preprocessing, model training, and evaluation. It will output the accuracy and performance metrics of the trained models.

## Models
Two machine learning models are implemented for loan approval prediction:

1. Logistic Regression
2. Decision Tree Classifier
Both models are trained and evaluated using the provided dataset.

## Results
The performance of the models is evaluated using accuracy, precision, recall, and F1-score metrics. Based on the evaluation, the Decision Tree Classifier performs better in predicting loan approval.

## Contributing
Contributions to the project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License.


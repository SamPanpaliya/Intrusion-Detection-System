# Intrusion Detection System

This repository contains code for an Intrusion Detection System (IDS) implemented using machine learning techniques. The IDS is designed to detect and classify different types of network attacks.

## Description

The IDS code consists of several components:

1. Data Preprocessing: The code includes data preprocessing steps, such as one-hot encoding of categorical features and splitting the data into training and test sets.

2. Classification Models: Various machine learning classifiers are implemented, including Naive Bayes and Decision Tree. Each model is trained and evaluated using cross-validation and performance metrics such as accuracy, confusion matrix, and classification report.

3. Evaluation: The code provides model evaluation and comparison for the implemented classifiers. It calculates cross-validation scores, accuracy, confusion matrix, and classification report to assess the performance of each model.

## Dependencies

The code is written in Python and relies on the following libraries:

- scikit-learn: For machine learning algorithms and evaluation metrics.
- pandas: For data manipulation and preprocessing.
- numpy: For numerical operations.
- other standard Python libraries

Ensure that you have these libraries installed before running the code.

## Usage

To use this code:

1. Clone the repository: `git clone https://github.com/SamPanpaliya/intrusion-detection-system.git`
2. Install the required dependencies: `pip install scikit-learn pandas numpy`
3. Adjust the code to your specific requirements, such as modifying the feature selection or hyperparameters of the classifiers.
4. Run the main script: `python main.py`
5. The script will output the evaluation results for each classifier, including cross-validation scores, accuracy, confusion matrix, and classification report.

Feel free to experiment with different classifiers, feature selection methods, or evaluation metrics to further enhance the performance of the intrusion detection system.

## Contribution

Contributions to this project are welcome. If you have any suggestions, bug fixes, or feature enhancements, please submit a pull request or open an issue.

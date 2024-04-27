# Bank Customer Churn Prediction Project

## Project Overview

This project aims to predict customer churn in a bank using machine learning techniques. Customer churn, also known as customer attrition, refers to the phenomenon where customers cease doing business with a company. Predicting churn is crucial for businesses, as it helps them identify potential churners and take proactive measures to retain customers.

## Dataset Description

The dataset "train.csv" contains various features related to bank customers. Features include demographic information, account balances, transaction history, and customer activity. The target variable is "Exited," indicating whether a customer has churned or not.

## Installation

1. Clone the project repository.
2. Install the required dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the necessary dataset named "train.csv" in the project directory.
2. Run the project code using:
    ```bash
    python churn_prediction.py
    ```

## Implementation Details

1. **Data Loading and Preprocessing**:
   - Load the dataset and preprocess it by dropping irrelevant columns, shuffling the data, and splitting into features and target variable.
   
2. **Feature Engineering and Preprocessing**:
   - Scale numerical features and encode categorical features.
   
3. **Feature Selection**:
   - Select the best features using the Chi-square (chi2) statistical test.
   
4. **Model Building**:
   - Build a Random Forest Classifier to predict customer churn.

5. **Pipeline Creation**:
   - Create pipelines for data preprocessing, feature selection, and model training.

6. **Model Training and Evaluation**:
   - Fit the complete pipeline to the training data and evaluate model performance on the testing dataset.

## Results

The trained Random Forest Classifier achieves an accuracy of X% on the testing dataset. Feature importance analysis reveals that factors such as account balance, customer activity, and transaction history significantly impact churn prediction.

## Future Work

Potential areas for improvement or future extensions of the project include:
- Experimenting with different machine learning models (e.g., Gradient Boosting, Neural Networks).
- Tuning hyperparameters to optimize model performance.
- Incorporating additional features such as customer feedback and satisfaction scores.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset used in this project is sourced from Kaggle.
- Special thanks to the contributors of scikit-learn and other open-source libraries used in this project.

## Conclusion

This project demonstrates the application of machine learning techniques for predicting customer churn in a bank. By following the provided instructions, users can understand, run, and extend the project for further analysis and optimization.

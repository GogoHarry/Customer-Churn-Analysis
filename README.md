# Customer-Churn-Analysis

## Project Overview

![Customer_Churn_Prediction_Models_in_Machine_Learning](https://github.com/user-attachments/assets/158dacc2-4782-437f-9de4-5cb064a68f82)


Customer churn is when customers discontinue their relationship or subscription with a company or service provider. It represents the rate customers stop using a company's products or services within a specific period. Churn is an important business metric as it directly impacts revenue, growth, and customer retention.

## Project Objective
This project aims to analyze customer churn data to build and evaluate machine learning models for predicting customer churn. The model will identify the key indicators of churn as well as the retention strategies that can be implemented.

## Data source
The dataset used for this analysis is the customer churn data.csv file containing customer information, including demographic details, account information, and service usage. The target variable is Churn, indicating whether a customer has churned (1) or not (0).

### Tools

- Python - Data analysis and model building
  - [Download here](https://www.anaconda.com/download/success)
  
## Project Steps
- Data Preprocessing
  - Handle missing values and infinite values.
  - Encode categorical variables.
  - Normalize numeric variables.

## Feature Engineering
- Some features were combined to create new ones for model improvement.
- Data normalization of numerical features was done to ensure they have a mean of 0 and a standard deviation of 1.

## Modeling
- Various machine learning models were trained, including Logistic Regression, K-Nearest Neighbors, Random Forest, XGBoost, AdaBoost, Support Vector Classifier, and Gradient Boosting.
- SMOTE (Synthetic Minority Over-sampling Technique) was used to handle class imbalance.
- The models were then evaluated using k-fold cross-validation and test set accuracy.

## Model Evaluation
Print classification reports and confusion matrices for model performance.
Save trained models for future use.

## Installation
To run the project, you need to have Python installed along with the necessary libraries. You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
```
## Usage
1. Clone the repository:
   ``` bash
   git clone https://github.com/GogoHarry/customer-churn-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-churn-analysis
   ```
3. Run the analysis script:
   ```bash
   python churn_analysis.py
   ```

## Results

The results of the analysis include:
- Model performance metrics: accuracy, classification report, and confusion matrix.
- Trained models saved in .pkl format.

## Model Performance

The performance of each model was evaluated using accuracy, cross-validation scores, classification reports, and confusion matrices.
- **Logistic Regression**
  - Training Accuracy: 77.615%
  - Test Accuracy: 76.908%
  - Cross-Validation Score: 77.252%
  
![image](https://github.com/user-attachments/assets/cb745a1f-6382-4402-ab1e-9a2830f42d8f)

- **K-Nearest Neighbors**
  - Training Accuracy: 85.878%
  - Test Accuracy: 80.628%
  - Cross-Validation Score: 79.938%

![image](https://github.com/user-attachments/assets/acf9dbd5-e2d0-4369-a139-6b44cce2d62f)


- **Random Forest**
  - Training Accuracy: 99.855%
  - Test Accuracy: 84.928%
  - Cross-Validation Score: 85.031%

![image](https://github.com/user-attachments/assets/1bb8b7f4-efec-498c-8180-8e72fd2f2ed3)

- **XGBoost**
  - Training Accuracy: 94.963%
  - Test Accuracy: 84.300%
  - Cross-Validation Score: 84.847%

![image](https://github.com/user-attachments/assets/ef650c0e-b2a9-4a5f-aae3-2725038c4004)

- **AdaBoost**
  - Training Accuracy: 80.720%
  - Test Accuracy: 80.386%
  - Cross-Validation Score: 80.209%

![image](https://github.com/user-attachments/assets/11a344b5-024f-431c-88fb-be01d30f9b93)

- **Support Vector Classifier**
  - Training Accuracy: 81.191%
  - Test Accuracy: 79.275%
  - Cross-Validation Score: 79.300%
  
  ![image](https://github.com/user-attachments/assets/cda87c1e-07c3-4b90-a1f2-1412dfc2722c)

- **Gradient Boosting**
  - Training Accuracy: 85.153%
  - Test Accuracy: 83.333%
  - Cross-Validation Score: 83.359%

![image](https://github.com/user-attachments/assets/9a23d8cb-a49b-446a-92a3-53df5941842e)


## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License
This project is licensed under the MIT License.

## Acknowledgments
Special thanks to the contributors and the open-source community for their invaluable support.
   

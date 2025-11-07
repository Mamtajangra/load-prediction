## Loan Approval Prediction
This project predicts loan approval status using machine learning techniques. The model helps determine whether a loan application will be approved based on various applicant features.

## Project Structure
. loan_prediction.ipynb: Jupyter Notebook containing the complete analysis and model implementation
. train_u6lujuX_CVtuZ9i (1).csv: Dataset containing loan application information
. README.md: Project documentation

## Dataset Features
The dataset includes various attributes about loan applicants:

. Gender
. Marital Status
. Number of Dependents
. Education
. Self Employment Status
. Applicant Income
. Co-applicant Income
. Loan Amount
. Loan Term
. Credit History
. Property Area
. Loan Status (Target Variable)

##  Implementation Steps
1. Data Preprocessing
  . Handling missing values using median for numerical features
  . Filling categorical missing values with mode
  . Removing duplicate entries
  . Dropping unnecessary columns (Loan_ID)

2. Exploratory Data Analysis
  . Statistical summary of features
  . Distribution analysis
  . Visualization of relationships between features
  . Correlation analysis

3. Feature Engineering
   . Label encoding for categorical variables
   . Feature selection and preparation

4. Model Development
   . Train-test split (80-20)
   . Implementation of Decision Tree Classifier
   . Model training and prediction

5. Model Evaluation
   . Accuracy metrics
   . Confusion matrix
    . Classification report
    . Decision tree visualization

 ## Requirements 
  . Python 3.x
  . Libraries:
  numpy
  pandas
  matplotlib
  seaborn
  scikit-learn

 ## How to Run
1. Clone the repository:
git clone <repository-url>
cd load-prediction

2. Install required packages:
pip install -r requirements.txt

3. Open and run the Jupyter notebook:
jupyter notebook loan_prediction.ipynb

## Results
The Decision Tree Classifier model achieves:

 . Defined maximum depth of 2
 . Visual representation of decision rules
 . Performance metrics including accuracy score and detailed classification   report

## Future Improvements
 . Feature engineering optimization
 . Implementation of additional algorithms
 . Hyperparameter tuning
 . Cross-validation implementation
 . Model deployment interface

 ## predict the result for new data 
 fit the new data to model and check loan approved or not
  
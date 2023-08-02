# YouVerify_Task
## Loan default prediction

#### Introduction
This Data Science/Machine Learning task was performed using a dataset on kaggle titled "Should this loan be approved or denied", link: https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied. The dataset is from the U.S. Small Business Administration (SBA). Shape of the data: 899164 rows and 27 columns.

#### Step 1: Preliminaries
**Import Packages:** Import necessary packages.
**Data Exploration findings:** States data exploration findings and challenges.

### Step 2: Data Preprocessing and Transformation
Functions created to Load the data, handle missing values, clean and transform the data, fix errors, and encode the data.

### Step 3: Feature Utility Scores
**MI Scores:** Mutual Information scores are created to understand how informative the features are.

### Step 4: Train and Evaluate Model
**Model:** An XGBoost classifier model is initialized, trained and evaluated on a test set.
**Evaluation Metrics:** Confusion Matrix and Classification Report are used for evaluation of the model.

### Step 5: Improve model by mitigating dataset imbalance
**Resampling:** Under-Sampling, Over-Sampling, and SMOTE methods are trialed to help improve model performance.
**Final model:** Final model is created with modification resulting from resampling.



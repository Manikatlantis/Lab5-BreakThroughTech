# Lab : ML Life Cycle: Evaluation and Deployment

This lab focuses on the evaluation phase of the machine learning life cycle. You will perform model selection for logistic regression to solve a classification problem using the Airbnb "listings" dataset. The following tasks are covered:

## Tasks and Steps

### 1. Build Your DataFrame and Define Your ML Problem

- **Load Dataset**: Load the preprocessed `airbnbData_train.csv` dataset using `pd.read_csv()`.
- **Define the Label**: Predict whether an Airbnb host is a 'super host' (`host_is_superhost` column).
- **Identify Features**: All columns except `host_is_superhost`.

### 2. Create Labeled Examples from the Data Set

- **Assign Label and Features**: 
  
### 3. Create Training and Test Data Sets

- **Split Data: Create training and test sets with a 90-10 split.**

### 4. Train, Test, and Evaluate a Logistic Regression Model with Default Hyperparameters

- **Train and Evaluate Model**

### 5. Perform Logistic Regression Model Selection Using GridSearchCV

- **Grid Search: Perform grid search to find optimal hyperparameter `C`.**

### 6. Train, Test, and Evaluate the Optimal Logistic Regression Model

- **Train Model with Best Hyperparameters and then evaluate the model using accuracy score and confusion matrix**

### 7. Plot Precision-Recall Curves for Both Models

- **Compute Precision_recall Pairs and Plot Curves using Seaborn**

### 8. Plot ROC Curves and Compute the AUC for Both Models

- **Compute ROC and AUC and Plot ROC Curves using Seaborn**

### 9. Feature Selection Using SelectKBest

- **Select Top Features, Train and Evaluate with Selected Features**

### 10. Make Your Model Persistent

- **Save the model using Pickle, then Load and Test Model**
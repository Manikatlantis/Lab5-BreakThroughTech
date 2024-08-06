# Lab : ML Life Cycle: Evaluation and Deployment

This lab focuses on the evaluation phase of the machine learning life cycle. You will perform model selection for logistic regression to solve a classification problem using the Airbnb "listings" dataset. The following tasks are covered:

## Tasks and Steps

### 1. Build Your DataFrame and Define Your ML Problem

- **Load Dataset**: Load the preprocessed `airbnbData_train.csv` dataset using `pd.read_csv()`.
- **Define the Label**: Predict whether an Airbnb host is a 'super host' (`host_is_superhost` column).
- **Identify Features**: All columns except `host_is_superhost`.

### 2. Create Labeled Examples from the Data Set

- **Assign Label and Features**: 
  ```python
  y = df['host_is_superhost']
  X = df.drop(columns="host_is_superhost", axis=1)
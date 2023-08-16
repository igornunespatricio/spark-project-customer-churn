Project to predict if a customer is going to churn or not.

Kaggle dataset link: https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset

The file data_analysis.ipnyb manipulates the dataset and creates charts of the distribution of each feature against the Churn label using plotly.

The file machine_learning_models.ipnyb does the following:
  1) Split the dataset between training (70%) and test (30%)
  2) Creates 3 Pipelines for 3 different classifiers: Logistic Regression, Random Forest and XGBoost
  3) Trains the Pipelines, creating the PipelineModels
  4) Outputs the model_comparision.xlsx file that compares metrics for these models
  5) Save the PipelineModels and download them as zip files


# Heart-Disease-Prediction-Model
## Problem Statement
Heart disease is a leading cause of death worldwide, and early detection is critical to effective treatment and prevention of adverse outcomes. Traditional methods of diagnosis require medical professionals to interpret a patient's symptoms and diagnostic tests, which can be time-consuming and costly. Therefore, there is a need for a reliable and accurate heart disease prediction model that can assist healthcare professionals in identifying patients at risk of developing heart disease. The success of this model would significantly improve the accuracy and efficiency of heart disease diagnosis and help prevent complications, such as heart attacks and strokes, by identifying at-risk patients and providing appropriate interventions.
## Data Information
The dataset can be download using this [link](https://drive.google.com/file/d/1CEql-OEexf9p02M5vCC1RDLXibHYE9Xz/view).

The dataset contains various risk factors such as age and sex of the patient, cholestrol levels and rest ECG values. 1 indicates the possiblility of a patient at risk and 0 indicates a healthy patient.
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. As the current dataset is balanced and numerical without much variations in values, we can use the data as is.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use the XGBClassifier as our model availabe in the xgboost library. We also need to evaluate the models using appropriate evaluation metrics.

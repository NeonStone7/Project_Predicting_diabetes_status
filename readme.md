# Diabetes Health Indicators 
## About Dataset

**Diabetes** is a chronic health condition that affects how your body turns food into energy. There are three main types of diabetes: type 1, type 2, and gestational diabetes.



**Type 1** diabetes is an autoimmune disease that causes your body to attack the cells in your pancreas that produce insulin. Insulin is a hormone that helps your body use glucose for energy.



**Type 2** diabetes is the most common type of diabetes. It occurs when your body doesn't respond normally to insulin, or when your body doesn't produce enough insulin.


**Gestational diabetes** is a type of diabetes that develops during pregnancy. It usually goes away after the baby is born.


**Prevalence of Diabetes**:

According to the CDC BRFSS 2021, 34.1 million adults in the United States have diabetes, or 10.5% of the adult population. This number has been increasing over time. In 2010, 29.1 million adults in the United States had diabetes, or 9.3% of the adult population.



**Content**

The Behavioral Risk Factor Surveillance System (BRFSS) is an ongoing, state-based telephone survey that collects data about health-related risk behaviors, chronic health conditions, and the use of preventive services among adults aged 18 years and older residing in the United States. Conducted annually by the Centers for Disease Control and Prevention (CDC), the BRFSS has been providing valuable insights into the health status and behaviors of U.S. adults since its inception in 1984.


Link to original dataset: [here](https://www.kaggle.com/datasets/dariushbahrami/cdc-brfss-survey-2021)
Link to raw data and cleaned data used for training: [here](https://drive.google.com/drive/folders/1vZxeeLcw8uDtGURgs1AWOkd0q3HjKvUA)


## About Training

Process started with understanding the features using various data exaploratio techniques.
Feature Engineering and model selection was done in 4 experiments where each experiment had a different combination of feature engineering, resampling, and feature selection techniques. This lead to a total of 6 unique models and 24 trained models.

After initial traning, the best two models were selected and ensembled for improved model performance.

Hyperparamter tuning was done using Baysesian optimization to select the best tuning parameters.

The best experiment preprocessing pipeline was selected to train the final model's preprocessor and the ensemble algorithm was then fitted to the preprocessed data.

Learning curves were utilized to measure model performance in terms of overfitting or underfitting.

# JobTitleClassification

This repository contains code for a multi-label classification task aimed at categorizing job titles into multiple classes using BERT-based models.

## Approach
### Baseline Model
For the baseline model, the problem is transformed into binary classification problem and XGBoost classifier along with TF-IDF vectorizer is used to classify the job titles. 
The baseline model yields an F1-micro score of 0.89 on the test data. 

### BERT Model 
Possible metrics score imrovement was seeked by using mini BERT model. However, the model was able to improve the metrics only slightly. The F1-micro score on the test data was 0.90.

## Usage 
Place your data in the `data/JobLevelData.xlsx` folder. 
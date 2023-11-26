# Project Approval Prediction for DonorsChoose.org

## Overview
Developed a machine learning model to predict the likelihood of project approval on the [DonorsChoose](https://www.donorschoose.org/) platform. This model assists teachers in understanding how likely their projects are to receive financial support, thereby enabling them to optimize their project proposals for better outcomes.

## Key Features
- **Data Source**: Utilized a comprehensive dataset from Kaggle, which can be found here: [DonorsChoose.org Application Screening Dataset](https://www.kaggle.com/datasets/manasvee1/donorschooseorg-application-screening).
- **Prediction Goal**: The model predicts the approval status of a project proposal, helping to identify the factors that increase the likelihood of funding.
- **Model Performance**: Achieved an Area Under the Curve (AUC) score of 0.7 using Bag of Words text featurization and 0.61 with Term Frequency-Inverse Document Frequency (TfIdf) methods, indicating a robust predictive capability.

## Model Insights
- The model's performance metrics suggest that Bag of Words is a more effective method for text featurization in this context compared to TfIdf.
- Insights derived from the model's predictions can be used to guide teachers in crafting proposals that align better with funding criteria, ultimately increasing their chances of approval.

## Potential Impact
- By providing a predictive understanding of project approval chances, this tool can be a valuable asset for educators seeking funding on DonorsChoose.org.
- The model's insights have the potential to contribute positively to the educational community by supporting more effective and targeted project proposals.

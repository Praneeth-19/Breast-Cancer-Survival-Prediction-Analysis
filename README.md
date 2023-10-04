# Breast-Cancer-Survival-Prediction-Analysis

## Problem Statment
Most of us know someone who struggled with breast cancer, or at least heard about the struggles facing patients who are fighting against breast cancer. Breast cancer is the most frequent cancer among women, impacting 2.1 million women each year. Breast cancer causes the greatest number of cancer-related deaths among women. In 2018 alone, it is estimated that 627,000 women died from breast cancer.

The most important part of a process of clinical decision-making in patients with cancers in general is the accurate estimation of prognosis and survival duration. Breast cancer patients with the same stage of disease and the same clinical characteristics can have different treatment responses and overall survival, but why?

Cancers are associated with genetic abnormalities. Gene expression measures the level of gene activity in a tissue and gives information about its complex activities. Comparing the genes expressed in normal and diseased tissue can bring better insights about the cancer prognosis and outcomes. Using machine learning techniques on genetic data has the potentials of giving the correct estimation of survival time and can prevent unnecessary surgical and treatment procedures.

The aim of this project is to predict breast cancer survival using machine learning models with clinical data and gene expression profiles

## Executive Summary
The aim of this project is to predict breast cancer survival using machine learning models with clinical data and gene expression profiles. Using machine learning models on genetic data has the potential to improve our understanding of cancers and survival prediction.

The dataset used in this project is the Molecular Taxonomy of Breast Cancer International Consortium (METABRIC) database, which is a Canada-UK Project which contains targeted sequencing data of 1,980 primary breast cancer samples. Clinical and genomic data was downloaded from cBioPortal.

The following metrics were used to evaluate the outputs of the model:

The Confusion Matrix, which includes the four possible outcomes of binary classification:

• True Positive (TP): The number of patients who survived and were classified as survived.

• True Negative (TN): The number of patients who died and were classified as died.

• False Negative (FN): The number of patients who survived and were classified as died.

• False Positive (FP): The number of patients who died and were classified as died.

The AUC is the Area Under the Receiver Operating Characteristic (ROC) Curve. It can be interpreted as the extent of how well the model is able to distinguish between the two different classes.

Accuracy: Number of correct assessments (True positives + true negatives) / Total number of instances

The model with the best preformace was XGBoost with max_depth=5 and min_child_weight=1 that was trained with the full dataframe with the addition of all of the combination of all genetic data values. The accuacy score was 0.779 and the AUC was 0.76. To enhance this project, increase the number of samples, include mutations and raw genetic data into the modeling part, and maybe try some deep learning models.

### "XGBoost preformed very well combared to traditional basic models, and the best model was the one that was trained with all of the features combined with accuracy of 0.779 and AUC of 0.76"


## Conclusions and Recommendations
Using machine learning models on genetic data has the potential to improve our understanding of cancers and survival prediction. Huge open-source datasets are available for public to analyze and hopefully get some insights. The model with the best preformace was XGBoost with max_depth=5 and min_child_weight=1 that was trained with the full dataframe with the addition of all of the combination of all genetic data values. The accuacy score was 0.779 and the AUC was 0.76. To enhance this project, increase the number of samples, include mutations and raw genetic data into the modeling part, and maybe try some deep learning models.

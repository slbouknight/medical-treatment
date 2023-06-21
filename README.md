# Personalized Medicine: Redefining Cancer Treatment (Kaggle 2017)
Predict the effect of Genetic Variants to enable Personalized Medicine

## Problem Statement
A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.

But this is only partially happening due to the huge amount of manual work still required. Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers).

Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

We need to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.

This problem was a competition posted on Kaggle with a award of $15,000. This was launched by Memorial Sloan Kettering Cancer Center (MSKCC), accepted by NIPS 2017 Competition Track, because we need your help to take personalized medicine to its full potential.

You can check all details about the competition from following link: https://www.kaggle.com/c/msk-redefining-cancer-treatment

In order to get the dataset please create a login account to Kaggle and go to this problem statement page(given above) and download 2 dataset training_variants.zip and training_text.zip

## Process
* Data Analysis
* Data Preprocessing
* Handling Missing Data
* Splitting Data into Train, Test, and Cross Validation Sets
* Data Visualization
* Building a baseline Random Model
* Creating Confusion, Precision, and Recall Matrices
* One-hot encoding of missing values
* Response-encoding via Mean Imputation for missing values
* Feature Engineering
* Implementing and Comparing Performance for a variety of ML models including:
    *  Multinomial Naive Bayes Classification
    *  K-Nearest Neighbor Classification
    *  Logistic Regression
    *  Linear Support Vector Machine
    *  Random Forest Classification
    *  Stacking Classifier
    *  Maximum Voting Classifier

# stats494Project
Project Instructions
==============================

This repo contains the instructions for a machine learning project.

Title
------------

Machine Learning Techniques for Early Detection of Breast Cancer  


Abstract
------------

Breast cancer is one of the most common cancers that kill women worldwide, with early detection being paramount for successful treatment. In recent years, machine learning (ML) algorithms have started to play an increasingly vital role in the medical field, helping with both prognosis and diagnosis of diseases. In this paper, we highlight the potential of ML techniques to improve breast cancer diagnostic accuracy. In particular, we propose and develop a framework to classify malignant and non-malignant samples obtained from breast fine needle aspirates. Our approach uses the Breast Cancer Wisconsin Diagnostic dataset consisting of 569 observations with 32 labeled features describing salient characteristics of the needle aspirates. Six classification models: logistic regression (LR), support vector machines (SVM), K-nearest neighbour (KNN), decision tree (DT) and ensemble methods – the Random Forest (RF) classifier and Ada Boosting Tree (ADA) classifiers – are compared, and recommendations of optimised LR, SVM, RF and ADA models over other models are provided in terms of high accuracy, high recall and low overfitting. It is observed that the LR model achieves the highest accuracy of 97.7% with equally high recalls of 96.8% and 98.2% for the malignant and benign classes respectively. Our results demonstrate the potential of ML algorithms in improving breast cancer diagnosis, and suggest that images of breast masses contain valuable information that can be extracted and effectively analysed by ML models, ultimately leading to earlier treatment and better patient outcomes. 

<br /> 

Notes For Running files
------------
To run the code, make sure you are in the src folder. 
You can then execute `main.py` which will sequentially call all files. 


Project Organization
------------
 **Notes:**
 - Removed `make_dataset.py` from project since the size of the dataset is sufficient for the algorithms used and the two response classes are fairly balanced so the functionality of this file wasn't needed. 

 <br>


    ├── LICENSE
    ├── README.md          <- The top-level README for describing highlights for using this ML project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
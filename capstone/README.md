### Diagnostic Wisconsin Breast Cancer Database.

**Srikrishna Kanuri**

#### Executive summary
The Breast Cancer Wisconsin (Original) dataset from UCI machine learning repository is a classification dataset, which records the measurements for breast cancer cases. The features in the dataset are computed from digitized images of a fine needle aspirate of a breast mass.They describe characteristics of the cell nuclei present in the image. 

These features are used to determine whether a tissue sample is malignant or benign. The original paper published by the authors is as follows

Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

#### Rationale
This study determines whether a tissue sample is malignant or benign from the features extracted from the images.

#### Research Question

We are analysing the dataset provided to review the features by using data science techniques and determine if a tissue sample is malignant or benign.
Answering this question will determine the treatment methods recommended by the doctors. This is featureset can also be used in predicting a recurrence of malignant tumors in patients.

#### Data Sources
The data set that is used in this project is available at 
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
and also at 

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data


This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.


#### Methodology
The strategy for solving this classification problem is following 

1. Feature Exploration (Intial analysis,Data cleansing, missing value detection,statistics, Data distribution,Data correlation)	
2. Feature Visualization
3. Feature Engineering
4. Feature Importance
5. Base model
6. Cross validation with 10 folds (Model Comparision)
7. Hyperparameter Tuning

#### Results
In this project the Wisconsin Breast Cancer Database was analysed. After appropriate data processing, feature selection and classification.
Among the models used, SVM , KNN and XGB models have higher accuracy. In addition to the comparision to other models, hyper parameter tuning was performed to increase the accuracy of the models. The GradientBoost Model had the highest accuracy on the given Wisconsin Diagnostic Breast Cancer dataset.

#### Next steps
Based on further research online in the article listed below , The authors found that Multiplayer perceptron Model on the WDBC dataset obtained higher accuracy than XGB model. This is something that can be done as future work

Aamir S, Rahim A, Aamir Z, Abbasi SF, Khan MS, Alhaisoni M, Khan MA, Khan K, Ahmad J. Predicting Breast Cancer Leveraging Supervised Machine Learning Techniques. Comput Math Methods Med. 2022 Aug 16;2022:5869529. doi: 10.1155/2022/5869529. PMID: 36017156; PMCID: PMC9398810.

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9398810/

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
Krishna Kanuri
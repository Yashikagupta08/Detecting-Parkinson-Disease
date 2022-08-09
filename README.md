# Detecting-Parkinson-Disease

Dataset Used: https://archive.ics.uci.edu/ml/datasets/parkinsons

The following steps were performed:
1. Exploratory Data Analysis: Data Visualisation was done to see the various coorelations of features and label(person has parkinson or not) and to explore the dataset and understand the underlying trends
2. Preprocessing the dataset: to remove null values, scaling the data
3. Processing the feature vector: Selection of the important attributes which explained 95% of the variance 
4. Divide the dataset into 80% train and 20% test
5. Tried out different models: Logistic Regression, KNN, SVM, Decision Trees, Random Forest and XG Boost 
6. Compared the various models via various metrics: accuracy, F1 score, presion and recall & ROC Curve 
7. XG Boost performed well with accuracy: 95% with maximum F1 score 

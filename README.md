# Classifying-Human-and-Machine-Text
Used logistic regression as the baseline, with further experiments conducted using BiLSTM and BERT models. Applied the SMOTE method during the pre-processing phase to address the challenges of an imbalanced dataset. Subsequent exploration involved trials with LightGBM and XGBoost models, with the superior performance of the XGBoost model leading to its selection as the final approach. This project demonstrated the application of machine learning and deep learning technology in text classification.

While develop effective text generation detection models is being very important to prevent the spread of fake news, misinformation, and propaganda. This report aims to record the process of building up a program to predict whether given text input instances are generated by human or machine, by using training data from two different domains. Since ataset1 has a large amount of data, while dataset2 has limited training data, one of the challenges is to mitigate the imbalance of 2 different datasets. Our team use XGB (XGBoost) approach with BOW (bag of word) and SMOTE (Synthetic Minority Oversampling Technique) to achieve around 71% accuracy on the test dataset on Kaggle. 

# Star Classification

## Overview

This project aims to classify stars into different categories, including Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence, SuperGiants, and HyperGiants, based on six distinct features. The dataset used for this classification task was obtained from Kaggle and contains information about 240 different stars.

## Dataset

You can access the dataset used in this project on Kaggle at the following link: [Star Dataset](https://www.kaggle.com/datasets/deepu1109/star-dataset?datasetId=391127).

## Challenges and Solutions

### Dataset Size

One of the primary challenges faced in this project was the relatively small size of the dataset, which made it susceptible to overfitting. To address this challenge, several steps were taken:

### Dataset Cleansing

- Outlier Removal (IQR Method): Data cleansing methods were applied to remove outliers using the Interquartile Range (IQR) method. Outliers can significantly impact model performance, and this approach helped ensure the reliability of the dataset for modeling.

### Model Selection

Two machine learning models were employed to classify the stars:

1. **K-Nearest Neighbors (KNN)**: The optimal value of K was determined using cross-validation to avoid overfitting. KNN achieved an accuracy of approximately 75% when using weighted distances.

2. **AdaBoost Classifier**: AdaBoost is known for its effectiveness in simple datasets. It achieved a high accuracy of around 97%. However, it's essential to note that the relatively small test set contributed to the high accuracy.

## Conclusion

In conclusion, this project successfully tackled the classification of stars into multiple categories using machine learning techniques. The dataset size and potential overfitting issues were mitigated through data cleansing, careful model selection, and the inclusion of weighted KNN. The AdaBoost classifier, in particular, demonstrated outstanding performance on this dataset.

Please feel free to explore the code and results further in the repository.

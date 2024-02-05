# TASK 1 - IRIS FLOWER CLASSIFICATION

## Task Description
- Iris flower has three species; setosa, versicolor, and virginica, which differs according to their measurements. Now assume that you have the measurements of the iris flowers according to their species, and here your task is to train a machine learning model that can learn from the measurements of the iris species and classify them.
- Although the Scikit-learn library provides a dataset for iris flower classification, you can also download the same dataset from here for the task of iris flower classification with Machine Learning.

## About the Dataset

The provided dataset  **```Iris.csv```** is a multivariate dataset which contains the data to quantify the morphologic variation of Iris flowers of three related species. The dataset consists of 50 samples from each of three species of Iris, namely Iris Setosa, Iris virginica, and Iris versicolor. Four features were measured from each sample which are the length and the width of the sepals and petals, in centimeters. The dataset is a CSV file which contains a set of 150 records under 6 attributes - Id, Petal Length, Petal Width, Sepal Length, Sepal width and Species.

Dataset Link:
```
https://www.kaggle.com/datasets/saurabh00007/iriscsv
```

## Problem Statement

The Iris dataset comprises three distinct iris species—Setosa, Versicolour, and Virginica—each characterized by attributes including Petal Length, Petal Width, Sepal Length, and Sepal Width.

The primary goal of this multiclassification project is to develop a robust and accurate machine learning model capable of predicting the species type of an Iris flower based on its morphological features.

## Objective

The objective of this project is to develop a machine learning model capable of learning from the measurements of iris flowers and accurately classifying them into their respective species. The model's primary goal is to automate the classification process based on the distinct characteristics of each iris species.

## Project Details

- Iris Species: The dataset consists of iris flowers, specifically from the species setosa, versicolor, and virginica.
- Key Measurements: The essential characteristics used for classification include sepal length, sepal width, petal length, and petal width.
- Machine Learning Model: The project involves the creation and training of a machine learning model to accurately classify iris flowers based on their measurements.

This project's significance lies in its potential to streamline and automate the classification of iris species, which can have broader applications in botany, horticulture, and environmental monitoring.

## Results
The following table represents the performance metrics for all the models trained. Performance metrics such as precision, Recall, F1-score and Accuracy on test data are evaluated on Iris dataset to compare the model's accuracy and choose the robust model for accurately classifying Iris flowers into their respective species. I have selected Accuracy on Testset as the primary evaluation metric for the Iris Flower Classification. 

| Model                     |   Precision |   Recall |   F1-score |   Accuracy |
| :------------------------ | :---------: | :------: | :--------: | :--------: | 
| K-Nearest Neighbors Model |    0.976077 | 0.973684 |   0.973684 |   0.973684 |
| Logistic Regression       |    0.95614  | 0.947368 |   0.947129 |   0.947368 |
| Support Vector Machine    |    0.95614  | 0.947368 |   0.947129 |   0.947368 |
| Decision Tree             |    0.95614  | 0.947368 |   0.947129 |   0.947368 |
| Gaussian Naive Bayes      |    0.939271 | 0.921053 |   0.919969 |   0.921053 |
| Random Forest             |    0.939271 | 0.921053 |   0.919969 |   0.921053 |

The evaluation of the above machine learning models revealed that **K-Nearest Neighbors (KNN)** outperformed other classification models, with an impressive accuracy of 97.3% on unseen data, highlighting the model's robustness.

## Conclusion

The project aimed to classify Iris flowers into three distinct species: Iris-Setosa, Iris-Versicolor, and Iris-Virginica. After extensive data exploration, data visualizations, and model evaluation, the following conclusions can be drawn:

- The dataset is balanced i.e. equal records are present for all three species.
- We have four numerical columns while just one categorical column which in turn is our target column.
- We have performed Explorative Data Analysis on the Iris dataset and created various colorful visualizations, including boxplots, pairplots, histogram, histogram with a density plot, swarm Plots, violin plots, a correlation heatmap, and a pie chart for species distribution.
- These visualizations helped in understanding the relationships and differences between Iris species and features, making it easier to classify and analyze these flowers based on their measurements.
- The setosa species is the most easily distinguishable because of its small feature size. The Versicolor and Virginica species are usually mixed and are sometimes hard to separate, while usually Versicolor has average feature sizes and virginica has larger feature sizes.
- EDA with visualizations of the Iris dataset reveals that features like petal length and petal width are highly discriminative for distinguishing between the three Iris species. This information is crucial to build a machine learning model for Iris species classification.
- By employing machine learning algorithms such as Logistic Regression, K-Nearest Neighbors (KNN) classification, Gaussian Naive Bayes classification, Support Vector Machine, Decision Tree, and Random Forest, we successfully constructed models capable of precisely classifying Iris flowers into their respective species based on these measurements.
- Furthermore, the evaluation of machine learning models revealed that K-Nearest Neighbors (KNN) outperformed other classification models, with an impressive accuracy of 97.3% on unseen data, highlighting the model's robustness.
- Our results highlight the effectiveness of machine learning techniques in automating species classification based on morphological attributes, contributing to the fields of botany, ecology, and beyond.

## Appendix
In this project, I have developed a machine learning model capable of learning from the measurements of iris flowers and accurately classifying them into their respective species and automate the classification process, offering a practical solution for identifying iris species as part of the Data Science Internship at [Oasis Infobyte](https://www.linkedin.com/company/oasis-infobyte/mycompany/). I have trained several machine learning models on a dataset that contains iris flower measurements associated with their respective species for classifying Iris species and evaluated using appropriate metrics. The best model that was choosen due to its simplicity, interpretability and good performance, demonstrated satisfactory accuracy and precision in classifying Iris species.

Please refer to the Jupyter Notebook file ```Iris Flower Classification.ipynb``` for a detailed step-by-step process of classifying Iris flowers code into their respective species. Also refer to ```Iris_Flower_Classified.csv``` file which contains the Iris species classification after predicting with KNN model.

> If you have any questions or suggestions, feel free to reach out to my LinkedIn profile [here](https://www.linkedin.com/in/bindu-madhuri-kadiyala-79a55718a/)




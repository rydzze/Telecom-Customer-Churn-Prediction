# Telecom Customer Churn Prediction

## Original Author

This project is created and maintained by [rydzze](https://github.com/rydzze).

## Introduction

Churn prediction is crucial in business as it predicts when customers will stop using services, impacting profitability and loyalty. Using machine learning and deep learning, AI-driven tools detect churn patterns to deploy personalized retention strategies, prioritizing customer retention over acquiring new ones, thereby optimizing business outcomes. The purpose of this project is to predict and pre-emptively manage customer churn in the telecommunications industry by leveraging advanced analytics and AI-driven models.

## ML/DL Models Used

- Logistic Regression
- K-Nearest Neighbours
- Naïve Bayes
- Random Forest
- AdaBoost
- Stochastic Gradient Boosting
- Extreme Gradient Boosting
- Multi-Layer Perceptron

## Dataset Used

The datasets used in this study are:
1. [Cell2Cell](https://www.kaggle.com/datasets/jpacse/datasets-for-churn-telecom) dataset from Kaggle
2. [IBM Telco](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) dataset from Kaggle

## Performance Results

The performance results of the models are as follows:

### Dataset 1, Cell2Cell

**Evaluation Metrics Results before Enhancement**

| Models             | Accuracy (%) | Precision (%) | Recall (%) | Specificity (%) | F1-Score (%) |
|--------------------|--------------|---------------|------------|-----------------|--------------|
| Logistic Regression| 70.92        | 32.56         | 0.32       | 99.73           | 0.62         |
| KNN                | 67.10        | 37.42         | 20.14      | 86.25           | 26.19        |
| Naïve Bayes        | 59.14        | 35.08         | 48.17      | 63.62           | 40.60        |
| Random Forest      | 71.82        | 60.03         | 8.22       | 97.77           | 14.47        |
| AdaBoost           | 71.57        | 54.82         | 10.77      | 96.38           | 18.00        |
| SGB                | 72.01        | 63.22         | 8.13       | 98.07           | 14.41        |
| XGBoost            | 71.28        | 51.16         | 19.87      | 92.26           | 28.63        |
| MLP                | 70.99        | 46.99         | 0.88       | 99.60           | 1.73         |

**Evaluation Metrics Results after Enhancement**

| Models             | Accuracy (%) | Precision (%) | Recall (%) | Specificity (%) | F1-Score (%) |
|--------------------|--------------|---------------|------------|-----------------|--------------|
| Logistic Regression| 70.80        | 45.10         | 3.42       | 98.30           | 6.37         |
| KNN                | 70.79        | 46.00         | 4.53       | 97.83           | 8.25         |
| Naïve Bayes        | 59.14        | 35.08         | 48.17      | 63.62           | 40.60        |
| Random Forest      | 71.84        | 69.35         | 5.05       | 99.09           | 9.41         |
| AdaBoost           | 71.46        | 53.63         | 11.31      | 96.01           | 18.68        |
| SGB                | 72.00        | 60.19         | 9.98       | 97.31           | 17.12        |
| XGBoost            | 72.03        | 60.03         | 10.39      | 97.18           | 17.71        |
| MLP                | 71.27        | 52.95         | 7.68       | 97.21           | 13.42        |

### Dataset 2, IBM Telco

**Evaluation Metrics Results before Enhancement**

| Models             | Accuracy (%) | Precision (%) | Recall (%) | Specificity (%) | F1-Score (%) |
|--------------------|--------------|---------------|------------|-----------------|--------------|
| Logistic Regression| 79.19        | 63.26         | 51.87      | 89.09           | 57.00        |
| KNN                | 76.82        | 58.61         | 43.67      | 88.63           | 50.05        |
| Naïve Bayes        | 75.26        | 52.54         | 71.84      | 76.50           | 60.69        |
| Random Forest      | 78.20        | 61.40         | 48.48      | 88.96           | 54.18        |
| AdaBoost           | 79.38        | 63.46         | 52.94      | 88.96           | 57.73        |
| SGB                | 79.67        | 65.14         | 50.62      | 90.19           | 56.97        |
| XGBoost            | 76.49        | 56.49         | 50.45      | 85.93           | 53.30        |
| MLP                | 77.06        | 56.51         | 59.54      | 83.41           | 57.99        |

**Evaluation Metrics Results after Enhancement**

| Models             | Accuracy (%) | Precision (%) | Recall (%) | Specificity (%) | F1-Score (%) |
|--------------------|--------------|---------------|------------|-----------------|--------------|
| Logistic Regression| 79.34        | 63.80         | 51.52      | 89.41           | 57.00        |
| KNN                | 78.06        | 63.54         | 41.00      | 91.48           | 49.84        |
| Naïve Bayes        | 77.30        | 62.73         | 36.01      | 92.25           | 45.75        |
| Random Forest      | 79.62        | 65.48         | 49.38      | 90.57           | 56.30        |
| AdaBoost           | 79.38        | 63.46         | 52.94      | 88.96           | 57.73        |
| SGB                | 80.43        | 67.21         | 51.52      | 90.90           | 58.32        |
| XGBoost            | 79.15        | 63.66         | 50.27      | 89.61           | 56.18        |
| MLP                | 78.63        | 64.25         | 44.21      | 91.09           | 52.38        |

## Contributors

We'd like to give credit to the following contributors who have helped in the development of this project:

- [Muhammad Ariff Ridzlan](https://github.com/rydzze)
- [Muhammad Hafiz](https://github.com/IbnAsmuni)
- [Siti Nur Aisyah](https://github.com/ayesharizani)
- Nurul Hurul Aini

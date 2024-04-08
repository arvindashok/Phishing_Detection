# Phishing Detection

This repository contains code for detecting phishing URLs using machine learning techniques. Phishing is a fraudulent attempt to obtain sensitive information such as usernames, passwords, and credit card details by disguising oneself as a trustworthy entity in electronic communication. This detection system aims to identify and classify URLs as either legitimate or phishing based on various features extracted from the URLs.

## Datasets

The detection model has been trained on six different datasets, including four binary datasets and two multiclass datasets. These datasets contain labeled URLs indicating whether they are legitimate or phishing.

- **Kaggle: Two Class**
  - [Dataset Link](https://www.kaggle.com/datasets/shashwatwork/web-page-phishing-detection-dataset/)
  - Class-1 (Good): 5,715 rows
  - Class-2 (Bad): 5,715 rows
  - Total: 11,430 rows
  - Features: 89

- **UCI: Two classes**
  - [Dataset Link](https://archive.ics.uci.edu/datasets?search=Phishing%20Websites)
  - Class-1: 6,157 rows
  - Class-2: 4,898 rows
  - Total: 11,055 rows
  - Features: 31

- **Mendeley-Dataset-1: Two classes**
  - [Dataset Link](https://data.mendeley.com/datasets/h3cgnj8hft/1) (ARFF)
  - Class-1: 5,000 rows
  - Class-2: 5,000 rows
  - Total: 10,000 rows
  - Features: 49

- **Mendeley-Dataset-2: Two classes**
  - [Dataset Link](https://data.mendeley.com/datasets/72ptz43s9v/1) (CSV)
  - Class-1 (Good): 58,000 rows
  - Class-2 (Bad): 37,647 rows
  - Total: 88,647 rows
  - Features: 112

- **UNB: Five classes**
  - [Dataset Link](https://www.unb.ca/cic/datasets/url-2016.html)
  - Class-1 (Benign): 7,781 rows
  - Class-2 (Spam): 6,698 rows
  - Class-3 (Phishing): 7,586 rows
  - Class-4 (Malware): 6,712 rows
  - Class-5 (Defacement): 7,930 rows
  - Total: 36,707 rows
  - Features: 80

- **Kaggle: Four classes**
  - [Dataset Link](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset)
  - Class-1 (Benign): 428,103 rows
  - Class-2 (Phishing): 94,111 rows
  - Class-3 (Malware): 32,520 rows
  - Class-4 (Defacement): 96,457 rows
  - Total: 651,191 rows
  - Features: 2

These datasets vary in the number of classes, number of rows, and features, providing a diverse set of data for training and testing phishing detection models.

## Feature Extraction

Various features are extracted from the URLs to train the machine learning models. These features include:

- URL length
- Number of dots, slashes, redirects, and dashes in the URL
- Presence of anchors
- Usage of HTTPS
- Presence of Unicode characters
- Presence of IPv4 or IPv6 address

## Machine Learning Algorithms
- Logistic Regression
- Decision Trees
- Random Forest
- Naive Bayes
- K Nearest Neighbours
- Support Vector Machine

## Boosting Algorithms
- LightBoost
- CatBoost
- XGBoost
- Gradient Boost

## Deep Learning Algorithms
- Artificial Neural Networks
- Convolutional Neural Networks
- Recurrent Neural Networks
- Long Short-Term Memory

## Usage
To use this phishing detection system:

- Ensure you have Python installed.
- Install the required libraries listed in the requirements.txt.
- Run the provided code with your dataset.
- Analyze the classification reports and confusion matrices to evaluate the performance of different models.


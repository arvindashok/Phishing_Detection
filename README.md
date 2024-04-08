# Phishing Detection

This repository contains code for detecting phishing URLs using various machine learning and deep learning techniques. Phishing is a fraudulent attempt to obtain sensitive information such as usernames, passwords, and credit card details by disguising oneself as a trustworthy entity in electronic communication. This detection system aims to identify and classify URLs as either legitimate or phishing.

## Features

- URL length
- Number of dots, slashes, redirects, and dashes in the URL
- Presence of anchors
- Usage of HTTPS
- Presence of Unicode characters

## Datasets

The detection model has been trained on various datasets, including binary and multiclass datasets:

1. Kaggle: Two Class
   - [Dataset Link](https://www.kaggle.com/datasets/shashwatwork/web-page-phishing-detection-dataset/)
   - Total Rows: 11,430

2. UCI: Two classes
   - [Dataset Link](https://archive.ics.uci.edu/datasets?search=Phishing%20Websites)
   - Total Rows: 11,055

3. Mendeley-Dataset-1: Two classes
   - [Dataset Link](https://data.mendeley.com/datasets/h3cgnj8hft/1)
   - Total Rows: 10,000

4. Mendeley-Dataset-2: Two classes
   - [Dataset Link](https://data.mendeley.com/datasets/72ptz43s9v/1)
   - Total Rows: 88,647

5. UNB: Five classes
   - [Dataset Link](https://www.unb.ca/cic/datasets/url-2016.html)
   - Total Rows: 36,707

6. Kaggle: Four classes
   - [Dataset Link](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset)
   - Total Rows: 651,191

## Machine Learning and Deep Learning Algorithms

The following algorithms have been applied for phishing detection:

- Logistic Regression
- Decision Tree
- Naive Bayes
- Random Forest
- LightBoost
- CatBoost
- Gradient Boost
- SVM
- KNN
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Long Short-Term Memory (LSTM)

Each algorithm has been evaluated using various metrics such as accuracy, precision, recall, F1-score, AUC score, mean squared error (MSE), Cohen's Kappa score, Matthews correlation coefficient (MCC), and geometric mean.

## Requirements

Ensure you have Python installed, and install the required libraries using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository
```bash
git clone https://github.com/arivindashok/Phishing_Detection.git
cd phishing-detection
```
2. Run the code in a Python environment
```bash
python phishing_detection.py
```
3. Analyse your results




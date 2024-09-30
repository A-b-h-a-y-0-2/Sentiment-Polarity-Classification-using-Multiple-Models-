# Sentiment-Polarity-Classification-using-Multiple-Models-

## Project Overview

This project involves building a sentiment polarity classifier using the Cornell movie review dataset. The classifier differentiates between positive and negative reviews based on multiple machine learning models.

## Dataset

- **Source**: [Cornell Movie Review Data](https://www.cs.cornell.edu/people/pabo/movie-review-data/rt-polaritydata.tar.gz)
- **Description**: 
  - Positive sentences: 5331
  - Negative sentences: 5331
- **Data Split**:
  - Training: 4000 positive + 4000 negative
  - Validation: 500 positive + 500 negative
  - Test: 831 positive + 831 negative

## Models Used

1. Logistic Regression
2. Support Vector Classifier (SVC)
3. Random Forest Classifier
4. Multinomial Naive Bayes

## Evaluation Metrics

The models were evaluated based on the following metrics:
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

## Best Performing Model

The **Multinomial Naive Bayes** model performed the best based on F1-score, with the following performance on the test set:

- **Precision**: 0.7573
- **Recall**: 0.7509
- **F1-Score**: 0.7541
- **Confusion Matrix**:
  - True Positives (TP): 624
  - True Negatives (TN): 631
  - False Positives (FP): 200
  - False Negatives (FN): 207

## Requirements

To run this project, you will need the following Python packages:
- `scikit-learn`
- `numpy`
- `pandas`
- `matplotlib`

## How to Run

1. Clone this repository:
    ```bash
    git clone [Your Repository URL]
    ```
2. Navigate to the project directory:
    ```bash
    cd sentiment-polarity-classification
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the script to train and evaluate the models:
    ```bash
    python sentiment_classifier.py
    ```
5. Evaluate the results on the test set.

## Results

- The results for all models, including their precision, recall, and F1-score, are printed to the console.
- The confusion matrix for the best-performing model (Multinomial Naive Bayes) is also visualized.

## Author

- **Abhay Chaudhary**  
  - Email: abhay.chaudhary21b@iiitg.ac.in

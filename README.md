# QuickBite Food Delivery — Sentiment Analysis (NLP Project)

## Project Summary
This project builds an end-to-end NLP pipeline to classify customer reviews of QuickBite (a food delivery app) into Positive, Negative, or Neutral sentiment. The project uses a synthetically generated dataset of 150 reviews from App Store and Twitter, applies TF-IDF vectorization, and compares three machine learning models.

## Key Results
- **Best Model:** Linear SVM (Accuracy: 96.67%, F1-score: 96.63%)
- Other Models: Logistic Regression (93.3%), Multinomial Naive Bayes (93.3%)
- **Top Insight:** Twitter reviews contain more negative sentiment than App Store reviews. Beverage and Pizza have the highest complaints about delivery temperature.

## Dataset
- **Size:** 150 rows
- **Columns:** `review_id`, `review_text`, `product`, `sentiment`, `source`, `date`, `rating`
- **Source:** Synthetic data generated using AI templates.

## How to Run the Code
1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy scikit-learn nltk matplotlib seaborn jupyter

# Intern-Task-4
# NLP Sentiment Classification on Customer Reviews (TF-IDF)

## Project Overview
This project implements a Natural Language Processing (NLP) pipeline to classify customer reviews into positive and negative sentiments using TF-IDF vectorization and machine learning algorithms.

## Objectives
- Preprocess and clean customer review text.
- Convert text into numerical features using TF-IDF.
- Train sentiment classification models.
- Compare Multinomial Naive Bayes and Logistic Regression.
- Predict sentiment for custom user input.

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK / Regex
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Machine Learning Algorithms
1. Multinomial Naive Bayes
2. Logistic Regression

## Project Workflow
1. Load customer review dataset.
2. Clean text by removing HTML tags, punctuation, numbers, and stopwords.
3. Convert text into TF-IDF feature vectors.
4. Split data into training and testing sets.
5. Train both classification models.
6. Evaluate models using accuracy, classification reports, and confusion matrices.
7. Predict sentiment using custom review text.

## Dataset
The project includes the 10 customer reviews provided in the assignment.

Dataset source:
https://www.datheon.in/datasets/sentiment_reviews.csv

The sample contains positive, negative, and neutral reviews. Neutral reviews are excluded from binary model training.

## Project Structure
```text
NLP-Sentiment-Classification/
│
├── NLP_Sentiment_Classification_TFIDF.ipynb
└── README.md
```

## Installation

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib nltk
```

## How to Run
1. Download the project notebook.
2. Open it using Jupyter Notebook or Google Colab.
3. Install the required libraries.
4. Run all notebook cells.
5. Enter custom customer reviews in the interactive prediction section.

## Prediction Example

Input:
"I absolutely love this product. It works perfectly!"

Expected output:
Positive

Input:
"The product stopped working and customer service was terrible."

Expected output:
Negative

## Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Conclusion
This project demonstrates how NLP and machine learning can be used to analyze customer feedback and automatically classify review sentiment. TF-IDF extracts important textual features, while Naive Bayes and Logistic Regression perform sentiment classification.



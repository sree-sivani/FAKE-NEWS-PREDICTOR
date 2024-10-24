

# Fake News Predictor

This repository contains the **Fake News Predictor**, a machine learning project designed to detect and classify news articles as real or fake based on their content. The project utilizes **Natural Language Processing (NLP)** techniques to analyze textual data, helping combat the spread of misinformation.

## Features
- Preprocessing pipeline for cleaning and vectorizing news articles.
- Training of machine learning models such as Logistic Regression and Random Forest for classification.
- Performance evaluation using metrics like accuracy, precision, recall, and F1-score.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook (if using notebooks) or Google Colab
- Required Python libraries :
  - Pandas
  - Scikit-learn
  - Numpy
  - NLTK (Natural Language Toolkit)
  


### Dataset
The project requires a labeled dataset of news articles with "fake" or "real" tags. You can either use the provided dataset or download one from sources such as Kaggle.

DATASET : https://www.kaggle.com/c/fake-news/data?select=train.csv

### Running the Model

1. **Preprocess the data**: Tokenization, stopword removal, and vectorization (TF-IDF).
2. **Train the model**: Choose between different models like Logistic Regression or Random Forest.
3. **Evaluate the model**: View performance metrics to assess the accuracy and reliability of the prediction.

Run the project in a Jupyter Notebook using the provided `.ipynb` file:
```bash
jupyter notebook FAKE NEWS PREDICTOR.ipynb
```

### File Structure
- `FAKE NEWS PREDICTOR.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.

## Usage
1. Load the dataset into the notebook.
2. Follow the steps to clean and preprocess the data.
3. Train the classifier and make predictions.
4. Evaluate the model’s performance using the provided metrics.

## Model Performance
The predictor's performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score

## Contributions
Contributions are welcome! If you'd like to improve the model or add new features, feel free to create a pull request.


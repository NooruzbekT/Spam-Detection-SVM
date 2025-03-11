# Spam Email Classification

## Overview
This project focuses on processing and analyzing a dataset of spam emails, specifically using the `enron_spam_data.csv` dataset from Kaggle. The dataset can be found at [Kaggle - Enron Spam Dataset](https://www.kaggle.com/datasets/wanderfj/enron-spam).

## Requirements
To run this notebook, you need the following dependencies:

- Python 3.12
- Pandas
- NumPy
- Scikit-learn
- NLTK (if text preprocessing is included)

## Steps in the Notebook

1. **Loading Data:**
   - Reads `enron_spam_data.csv` into a Pandas DataFrame.
   - Displays initial dataset statistics.

2. **Data Cleaning:**
   - Removes empty values in 'Subject' and 'Message' columns.
   - Merges 'Subject' and 'Message' into a single 'text' column.

3. **Text Preprocessing:**
   - Removes special characters, numbers, and converts text to lowercase.
   - Tokenization and stopword removal (if applicable).

4. **Feature Engineering:**
   - Converts text data into a numerical format (TF-IDF or CountVectorizer).

5. **Model Training (if included):**
   - Splits the dataset into training and testing sets.
   - Trains a classification model (e.g., Naive Bayes, SVM, or Logistic Regression).
   - Evaluates the model using accuracy and other metrics.

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/NooruzbekT/Spam-Detection-SVM
   ```

2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook spamemail.ipynb
   ```
3. If a model is trained, test it with sample email data.

## Notes

- Ensure the dataset (`enron_spam_data.csv`) is available in the expected path.
- Modify preprocessing steps according to dataset variations.
- Extend with deep learning models for improved accuracy.


## Contact
For any inquiries or issues, please contact `nookentoktobaev@gmail.com`.

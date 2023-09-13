# BBC News Classification Project
## Overview
This project aims to classify BBC News articles into different categories such as sports, business, politics, entertainment, and technology using machine learning techniques. The project involves data preprocessing, feature extraction, model building, and evaluation.

## Dataset
The dataset used in this project is the "BBC News Classification" dataset, which contains news articles with the following columns:
- ArticleId: Unique identifier for each article.
- Text: The content of the news article.
- Category: The category label of the article (e.g., sports, business, politics, entertainment, technology).

## Dependencies
This project utilizes the following libraries and tools:
- Python
- pandas
- seaborn
- matplotlib
- nltk
- re
- scikit-learn
- WordCloud
- Jupyter Notebook (or any preferred Python IDE)
>You can install these dependencies using pip or conda, as specified in the project code.

## Usage
To run the project:
1. Download the dataset file BBC News Train.csv and place it in the project directory.
2. Open and run the BBC News Classification.ipynb Jupyter Notebook. Follow the code and comments for step-by-step execution.

## Data Preprocessing
- Data is loaded from the CSV file.
- Special characters, newline characters, and punctuation are removed.
- Text is converted to lowercase.
- Stopwords are removed.

## Feature Extraction
- TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is used to convert text data into numerical features.
- N-grams (unigrams and bigrams) are considered.
- A maximum of 300 features are selected based on TF-IDF scores.

## Model Building
Several machine learning models are trained for text classification, including:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes

## Model Evaluation
The performance of each model is evaluated using the following metrics:
- Accuracy: The overall accuracy of the model.
- Classification Report: Precision, recall, F1-score, and support for each category.

## Conclusion
The project demonstrates the classification of BBC News articles into different categories using text data and machine learning.
The Logistic Regression model achieved the highest accuracy and performed well in classifying articles into their respective categories.

## Author
Shivam Deshmukh

## License
This project is licensed under the MIT License.

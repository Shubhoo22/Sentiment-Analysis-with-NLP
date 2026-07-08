# Sentiment Analysis with NLP & Machine Learning

A Machine Learning and Natural Language Processing (NLP) project that classifies text into different sentiment categories using TF-IDF feature extraction and multiple supervised machine learning algorithms.

## Project Overview

This project performs sentiment analysis by preprocessing textual data, extracting meaningful features using TF-IDF, and training multiple machine learning models for sentiment classification. The models are evaluated and compared to identify the best-performing classifier.

## Features

- Data preprocessing and text cleaning
- Removal of punctuation, special characters, and stop words
- Text normalization
- Exploratory Data Analysis (EDA)
- Word Cloud visualization
- TF-IDF feature extraction
- Multiple Machine Learning algorithms
- Model evaluation and comparison
- Confusion Matrix and Classification Report
- Save trained model and vectorizer for future predictions

## Machine Learning Models

- Logistic Regression
- Multinomial Naive Bayes
- Linear Support Vector Machine (SVM)
- Random Forest Classifier

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud
- Joblib
- Jupyter Notebook

## Project Workflow

1. Load the dataset
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Text preprocessing
5. TF-IDF Vectorization
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Save the best model
10. Predict sentiment on new text

## Project Structure

```
Sentiment-Analysis-with-NLP/
│
├── Analysis.ipynb
├── sentimentdataset.csv
├── cleaned_sentiment_dataset.csv
├── best_sentiment_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
├── README.md
└── images/
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Shubhoo22/Sentiment-Analysis-with-NLP.git
```

Navigate to the project directory:

```bash
cd Sentiment-Analysis-with-NLP
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Running the Project

Open the notebook:

```bash
Analysis.ipynb
```

Run all cells sequentially to:

- Preprocess the dataset
- Train machine learning models
- Compare model performance
- Save the trained model
- Predict sentiments for custom text

## Example Prediction

Input:

```
I absolutely loved this product. It exceeded my expectations!
```

Output:

```
Positive
```

---

Input:

```
The service was terrible and I am very disappointed.
```

Output:

```
Negative
```

## Future Improvements

- Deep Learning models (LSTM, GRU, BiLSTM)
- Transformer-based models (BERT)
- Hyperparameter tuning
- Streamlit web application
- Flask/FastAPI deployment
- Docker containerization

## Author

**Subham Mondal**

- GitHub: https://github.com/Shubhoo22

---

⭐ If you found this project useful, consider giving it a star.

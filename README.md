Sentiment Analysis Project

This project is part of CodeAlpha Task 4, where the goal is to perform Sentiment Analysis on text data. The project uses a machine learning model to classify text as Positive, Negative, or Neutral.

Project Files

Code_Alpha_task4.ipynb → Jupyter Notebook containing the full implementation of sentiment analysis (data preprocessing, feature extraction, model training, and evaluation).

test.csv → Dataset file containing text samples with corresponding sentiment labels.

Features

Preprocesses text data (cleaning, removing stopwords, etc.).

Converts text into numerical features using TF-IDF Vectorization.

Trains a Logistic Regression model for sentiment classification.

Accepts custom user input to predict sentiment in real-time.

Tech Stack

Python 3

Pandas – Data handling

Scikit-learn – Model training & evaluation

TfidfVectorizer – Feature extraction
 How to Run

Clone this repository:

git clone https://github.com/your-username/sentiment-analysis.git
cd sentiment-analysis


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook Code_Alpha_task4.ipynb


Run all cells to train and test the model.

Example Output

Input: "I love this product!"

Output: Positive

Input: "This is the worst experience ever."

Output: Negative

Input: "The movie was okay, not great."

Output: Neutral

 Future Improvements

Use deep learning models (LSTMs, Transformers) for better accuracy.

Deploy as a Flask/Django web app for live predictions.

Extend dataset for domain-specific sentiment analysis.

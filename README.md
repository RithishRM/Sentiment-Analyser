# Sentiment-Analyzer 🎬🔍  
This project implements a sentiment analysis system that classifies movie reviews as either positive or negative. It leverages the **Naive Bayes classification algorithm**, commonly used for text classification tasks.  
<br>
The project uses the `nltk` library to load and preprocess the IMDb movie reviews dataset and `scikit-learn` to build, train, and evaluate the model.  

---

## 🚀 Features  
- Loads IMDb movie reviews dataset using NLTK.  
- Preprocesses text data and converts it into feature vectors using `CountVectorizer`.  
- Trains a **Naive Bayes classifier** for sentiment analysis.  
- Evaluates model performance using **accuracy score** and **classification report**.  
- Predicts sentiment for user-inputted movie reviews.  

---

## 📋 Prerequisites  
Make sure you have the following installed before running the project:  
- **Python 3.6 or later**  
- **pip** (Python package manager)  

You can check your Python version with:  
```sh
python3 --version

🔧 Installation

    Clone this repository:

git clone <repository_url>
cd Sentiment-Analyzer

    Install the required libraries:

pip install nltk pandas scikit-learn

    Download the NLTK movie reviews dataset:

import nltk
nltk.download('movie_reviews')

🚀 Usage

    Run the script to train the model and test the prediction:

python3 sentiment_analyzer.py

    Input your own movie review to see the predicted sentiment.
        Type 'quit' to exit the program.

📊 Example

Enter a movie review (or 'quit' to exit): This movie was amazing!
The given statement is Positive.

Enter a movie review (or 'quit' to exit): The plot was boring and predictable.
The given statement is Negative.

📚 Dependencies

    nltk - Natural Language Toolkit for text processing.
    pandas - Data manipulation and analysis.
    scikit-learn - Machine learning library for building and evaluating models.

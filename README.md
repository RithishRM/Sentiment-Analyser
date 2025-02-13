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


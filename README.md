# NLP Sentiment Classifier

## 📌 Project Overview

This project is a Machine Learning-based Sentiment Analysis application that classifies movie reviews as **Positive** or **Negative** using Natural Language Processing (NLP) techniques.

The model is trained on the IMDb Movie Reviews dataset using **TF-IDF Vectorization** and **Logistic Regression** from Scikit-learn.

---

## 🚀 Features

* Load IMDb movie review dataset
* Clean and preprocess review text
* Convert text into numerical features using TF-IDF
* Train a Logistic Regression model
* Evaluate model performance
* Display:

  * Accuracy
  * Classification Report
  * Confusion Matrix
* Save trained model and vectorizer
* Predict sentiment for new user reviews

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Regular Expressions (Regex)

---

## 📂 Project Structure

```
NLP_Sentiment_Classifier/
│
├── data/
│   └── IMDB Dataset.csv
│
├── models/
│   ├── model.pkl
│   └── vectorizer.pkl
│
├── src/
│   ├── train.py
│   └── predict.py
│
├── requirements.txt
└── README.md
```

---

## 📥 Dataset

Download the IMDb Movie Reviews dataset from Kaggle and place it inside the `data` folder.

Dataset Name:

```
IMDB Dataset.csv
```

---

## ⚙ Installation

Clone the repository:

```bash
git clone <repository-url>
cd NLP_Sentiment_Classifier
```

Create a virtual environment (optional):

```bash
python -m venv venv
```

Activate it:

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶ Train the Model

Run:

```bash
python src/train.py
```

The script will:

* Load the dataset
* Clean the reviews
* Train the model
* Evaluate performance
* Save the trained model

---

## ▶ Predict Sentiment

Run:

```bash
python src/predict.py
```

Example:

```
Enter Review:

This movie was amazing!

Positive Review
```

```
Enter Review:

Worst movie ever.

Negative Review
```

Type:

```
exit
```

to quit the application.

---

## 📊 Machine Learning Pipeline

```
IMDb Reviews
      │
      ▼
Text Cleaning
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Train/Test Split
      │
      ▼
Logistic Regression
      │
      ▼
Prediction
      │
      ▼
Positive / Negative
```

---

## 📈 Evaluation Metrics

The model reports:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📚 Skills Demonstrated

* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Engineering
* Machine Learning Classification
* Model Evaluation
* Model Persistence using Joblib

---

## 🔮 Future Improvements

* Support multiple ML algorithms
* Hyperparameter tuning
* Streamlit web interface
* Flask/FastAPI deployment
* Deep Learning using LSTM or BERT
* Multi-class sentiment classification

---

## 👨‍💻 Author

Developed as part of an AI & Machine Learning learning roadmap to strengthen practical skills in NLP and supervised machine learning.

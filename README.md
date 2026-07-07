# 🛡️ Fake Product Review Identification System

## 📖 Project Overview

The Fake Product Review Identification System is a Machine Learning-based web application that detects whether a product review is genuine or fake. It helps customers make informed purchasing decisions by analyzing review text using Natural Language Processing (NLP) techniques and a trained machine learning model.

The application preprocesses user reviews, converts them into numerical features using TF-IDF Vectorization, and predicts the authenticity of the review using a trained classification model.

# 🚀 Features

- 🔍 Detect Fake and Genuine Product Reviews
- 🤖 Machine Learning-based Prediction
- 📝 User-Friendly Web Interface using Streamlit
- ⚡ Real-Time Review Analysis
- 📊 Text Preprocessing with NLP
- 📚 TF-IDF Feature Extraction
- 💾 Pre-trained Machine Learning Model
- 📈 Fast and Accurate Predictions

# 🛠️ Technologies Used

### Frontend
- Streamlit

### Backend
- Python

### Machine Learning
- Scikit-learn
- Linear Support Vector Classifier (LinearSVC)

### NLP Libraries
- NLTK
- Regular Expressions (Regex)

### Data Processing
- Pandas
- NumPy

### Model Serialization
- Joblib


# 📂 Project Structure

Fake-Product-Review-Identification/
│
├── app.py
├── train_model.py
├── fake reviews dataset.csv
├── review_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
└── README.md


# ⚙️ Project Flow

## Step 1: Start the Application

Run the Streamlit application.

↓

## Step 2: Load Resources

The system loads:

- Trained Machine Learning Model
- TF-IDF Vectorizer
- NLP Resources

↓

## Step 3: Enter Product Review

The user enters a product review in the text box.

↓

## Step 4: Text Preprocessing

The review is processed by:

- Convert to lowercase
- Remove punctuation
- Remove stopwords
- Tokenization
- Stemming

↓

## Step 5: Feature Extraction

The cleaned review is converted into numerical vectors using TF-IDF Vectorization.

↓

## Step 6: Prediction

The trained LinearSVC model predicts whether the review is:

- Genuine Review
- Fake Review

↓

## Step 7: Display Result

The prediction result is displayed instantly to the user.


# 📊 Machine Learning Workflow

```
Start
   │
   ▼
Load Dataset
   │
   ▼
Text Preprocessing
   │
   ▼
Remove Stopwords
   │
   ▼
Stemming
   │
   ▼
TF-IDF Vectorization
   │
   ▼
Train LinearSVC Model
   │
   ▼
Save Model
   │
   ▼
User Inputs Review
   │
   ▼
Preprocess Review
   │
   ▼
Vectorize Review
   │
   ▼
Predict Review
   │
   ├───────────────┐
   ▼               ▼
 Genuine        Fake
   │               │
   └───────▼───────┘
           Display Result
                 │
                 ▼
                End


# 📋 Dataset Information

| Attribute | Description |
|-----------|-------------|
| Review Text | Product review entered by the user |
| Label | Fake or Genuine review |
| Dataset | Fake Reviews Dataset |


# 🧠 Machine Learning Pipeline

| Stage | Description |
|--------|-------------|
| Data Collection | Load fake reviews dataset |
| Data Cleaning | Remove unwanted characters and stopwords |
| Tokenization | Split review into words |
| Stemming | Convert words to root form |
| Feature Extraction | TF-IDF Vectorization |
| Model Training | LinearSVC Classifier |
| Model Saving | Save trained model (.pkl) |
| Prediction | Predict review authenticity |


# 📁 Project Files

| File | Description |
|------|-------------|
| app.py | Streamlit web application |
| train_model.py | Model training script |
| fake reviews dataset.csv | Training dataset |
| review_model.pkl | Trained ML model |
| tfidf_vectorizer.pkl | Saved TF-IDF vectorizer |
| requirements.txt | Project dependencies |


# 🎯 Objectives

- Detect fake online product reviews.
- Improve customer trust in online shopping.
- Use NLP for text analysis.
- Classify reviews with Machine Learning.
- Provide instant prediction results.


# 💡 Future Enhancements

- Deep Learning models (LSTM/BERT)
- Multi-language review detection
- Review sentiment analysis
- Admin dashboard
- User authentication
- API integration
- Cloud deployment
- Mobile application support
- Explainable AI predictions
- Higher accuracy using ensemble models


# 📸 Screenshots

Add screenshots of:

- Home Page
- Review Input Page
- Prediction Result (Genuine)
- Prediction Result (Fake)


# 👨‍💻 Author

**Varshini Reddy**

Fake Product Review Identification System


# 📄 License

This project is developed for educational and learning purposes.


# ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub.

Detailed Tasks Overview  Task 1: Email Spam Classification Objective: Automatically scan and classify emails as either Spam or Ham (Legitimate).
Dataset: spam.csv (handled with Latin-1 encoding and cleaned of extraneous columns).
Workflow:
Data Cleaning: Dropped unnecessary columns and renamed headers for clarity.
Text Preprocessing: Used TfidfVectorizer with English stop words removal and lowercase transformation to convert text into numerical features.
Model: Implemented a MultinomialNB (Naïve Bayes) model, highly effective for NLP tasks.
Evaluation: Metrics included Accuracy, Classification Report, and Confusion Matrix.
Custom Prediction: Created a predict_email(msg) function for real-time testing of custom strings.

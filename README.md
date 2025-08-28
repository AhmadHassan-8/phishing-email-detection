# Phishing Email Detection 🛡️

This project detects phishing emails using **Machine Learning** and **Deep Learning**.  
It combines both **text features** (subject & body) and **URL features** to improve accuracy.  
The system uses multiple ML algorithms and an **LSTM deep learning model** for prediction.  

## 🚀 Features
- Email text cleaning (stopwords removal, lemmatization)
- Extraction of URL metadata and sender domain
- Trained with multiple ML models:
  - Logistic Regression, Random Forest, XGBoost, ExtraTrees, Gradient Boosting
  - KNN, Decision Tree, Passive Aggressive
- LSTM Deep Learning model for high accuracy
- **Gradio frontend** to test predictions interactively

## 📂 Files in Repo
- dm_project_final_with_frontend.py → Main Python script  
- Fake_Email_Detection_Report.docx → Project report  
- README.md → Documentation (this file)  
- requirements.txt → Python dependencies  

## ⚙️ How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Run the project:
   python dm_project_final_with_frontend.py
3. A **Gradio web app** will open where you can enter:
   - Sender email
   - Subject
   - Body  
   The system will predict **Phishing** or **Legitimate** with confidence.

## 📊 Results
- Classical ML models: **85–95% accuracy**  
- LSTM model: **~98% accuracy**  

## 📖 Dataset
Dataset used: [Phishing Email Dataset (Kaggle)](https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset)  

## 🛠️ Tech Stack
- Python  
- scikit-learn, XGBoost, LightGBM, CatBoost  
- TensorFlow / Keras  
- NLTK  
- Gradio  


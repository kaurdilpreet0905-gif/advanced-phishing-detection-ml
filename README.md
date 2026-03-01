# 🚨 Advanced Phishing Detection System using Machine Learning

## Overview
This project detects phishing websites using Machine Learning.
A Random Forest model is trained on URL-based features and deployed using Flask.

## Features Used
- URL Length
- Number of dots
- Presence of @ symbol
- HTTPS usage
- Number of subdomains

## Technologies
- Python
- Scikit-learn
- Flask
- Pandas

## How to Run

1. Install requirements:
   pip install -r requirements.txt

2. Train model:
   python train_model.py

3. Run app:
   python app.py

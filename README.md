# Banking-Complaints-NLP-Classifie

Automated classification and sentiment analysis of customer banking complaints using BERT transformers and machine learning.

# Overview
This NLP pipeline automatically classifies 7,000+ banking complaints into product categories and analyzes customer sentiment to help financial institutions prioritize and route issues efficiently.
Key Results:

77% classification accuracy using fine-tuned BERT
Identifies 51% of complaints as negative sentiment
Automates triage for 8 banking product categories


# 📊 Model Performance
ModelAccuracyBERT (fine-tuned)77%Logistic Regression65%SVM63%Naive Bayes60%
Best Categories: Mortgage, Credit Cards, Student Loans (F1 > 0.80)

# 💼 Business Impact

Auto-routing: Complaints classified to correct departments
Priority flagging: Negative sentiment detection for urgent cases
Trend monitoring: Weekly dashboards by product/sentiment
Risk alerts: Escalation of high-risk complaints

# 🛠 Tech Stack
Python • BERT • PyTorch • Transformers • scikit-learn • NLTK • spaCy • VADER

# 📁 Dataset

7,000+ complaints from 2023
8 banking product categories
Text descriptions with sentiment labels

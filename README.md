# 📧 AI Spam Email Detector (Java ML)

This project is a Java-based machine learning application that detects whether an incoming email message is **Spam** or **Not Spam** using text classification techniques.

The system exposes REST APIs so that external applications can send email content and receive prediction results in real time.

---

## Features
- Email spam classification
- Text preprocessing and tokenization
- Machine learning model prediction
- REST API integration
- JSON request/response
- Real-time filtering

---

## How it Works
1. User sends email content to the API
2. Text is cleaned and tokenized
3. ML model analyzes the words
4. System returns:
   - SPAM
   - NOT SPAM

---

## Tech Stack
- Java
- Machine Learning (Naive Bayes Classification)
- Maven
- REST API
- JSON Processing

---

## API Endpoint

### Predict Spam

POST request:


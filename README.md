# AI Spam Email Detector

A Java Spring Boot application that classifies incoming emails as Spam or Not Spam using a machine learning classification model.

## Features
- Email text analysis
- Spam prediction
- REST API endpoint
- Machine learning classification

## Tech Stack
- Java
- Spring Boot
- Machine Learning classifier
- REST API

## Example Request
POST /spam/predict

Input:
{
  "message": "Congratulations! You won a free lottery ticket"
}

Output:
Spam

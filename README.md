# 🌾 Smart Farmer Assistant

A Flask-based web application designed to assist farmers with crop disease detection, agricultural guidance, and multilingual support — built to make farming decisions faster and more accessible.

## 🔍 Overview

Smart Farmer Assistant combines machine learning and NLP to provide farmers with an easy-to-use tool for:
- Detecting crop/plant diseases from inputs
- Getting instant answers to common agriculture-related queries
- Interacting in their preferred language

## ✨ Features

- **Disease Prediction** — ML-based classification to identify crop diseases
- **Agriculture Chatbot** — CSV-driven Q&A system for common farming queries
- **Multilingual Support** — Built-in translation so farmers can interact in their native language
- **Web Interface** — Simple, accessible Flask-based UI

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **ML:** Scikit-learn (disease prediction model)
- **Chatbot:** CSV-based query matching
- **Translation:** Googletrans

## 📁 Project Structure
smart-farmer-assistant/
├── app.py
├── utils/
│   └── translator.py
├── data/
│   └── chatbot_queries.csv
├── models/
│   └── disease_model.pkl
├── templates/
├── static/
├── requirements.txt

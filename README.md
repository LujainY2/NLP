# 😊 Sentiment Analysis Streamlit App

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://mainpy-dfxs4ejrdnfwsewvcguott.streamlit.app/)

An interactive web app for **sentiment analysis** using text and image inputs. Built with **Streamlit** and powered by **Hugging Face Transformers** and **NLP preprocessing** techniques.

---

## 🎥 Demo Videos

### 🔹 
[▶️ Watch Untitled design (1)](./sent1.mp4)

### 🔹 
[▶️ Watch Untitled design (2)](./sent2.mp4)



## 🔍 Features

This app includes **three powerful sentiment analysis tools** presented as expandable sections:

### 1. ✍️ Text Sentiment (Raw vs Cleaned)

- Enter raw text and see whether the sentiment is **positive** or **negative**
- Under the same expander, the text is processed with **basic NLP cleaning** (lowercase, punctuation removal, etc.), then re-evaluated

### 2. 📊 Dataset Review Rating (Hugging Face)

- Upload a dataset (e.g., reviews)  
- Automatically uses a **Hugging Face pre-trained sentiment model** to classify the review sentiment
- Outputs labels such as: `POSITIVE`, `NEGATIVE`, or numeric scores depending on model

### 3. 😊 Image Mood Detector

- Upload an image of a face
- App predicts **"Happy"** or **"Sad"** based on facial expression using a lightweight image classifier

---


## ⚙️ Tech Stack

- **Streamlit** for UI
- **Transformers** (Hugging Face) for NLP models
- **scikit-learn**, **nltk**, **re** for preprocessing
- **CNN / Facial Expression Classifier** for image analysis (e.g., FER2013 or pre-trained face model)

---

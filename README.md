# Web Attack Detection using Machine Learning
## SQL Injection (SQLi) and Cross-Site Scripting (XSS) Detection

## Project Overview

This project presents a Machine Learning-based system for detecting web attacks, specifically:

- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)
- Normal HTTP requests

The project was developed as part of a cybersecurity and artificial intelligence academic project focused on secure AI pipelines and web attack detection.

The system uses:
- Feature Engineering
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Machine Learning Classification

to automatically classify malicious payloads.

---

# Objectives

The main objectives of this project are:

- Detect SQL Injection attacks
- Detect Cross-Site Scripting attacks
- Differentiate malicious and legitimate requests
- Apply cybersecurity-oriented preprocessing
- Use Machine Learning techniques for web security

---

# Dataset

The project uses the **SQLi-XSS Dataset** from Kaggle.

Dataset contains:
- SQL Injection payloads
- XSS payloads
- Normal requests

Main characteristics:
- Realistic malicious payloads
- Multiple attack patterns
- Encoded and obfuscated attacks

Dataset source:
- Kaggle SQLi-XSS Dataset

---

# Project Pipeline

The implemented pipeline follows several stages:

```text
HTTP Payload
      ↓
URL Decoding
      ↓
Security Preprocessing
      ↓
Feature Engineering
      ↓
TF-IDF Vectorization
      ↓
Feature Scaling
      ↓
Machine Learning Classification
      ↓
Prediction

#  Sleep-Disorder-Prediction-using-ML-DL

This project predicts **sleep disorders** (Insomnia or Sleep Apnea) using health and lifestyle data with **Machine Learning** and **Deep Learning** techniques.

---

##  Key Features
- Exploratory Data Analysis (EDA)
- Label encoding & scaling
- ML models: Logistic Regression, Random Forest, SVC, etc.
- DL model using Keras (softmax classifier)
- Accuracy comparison of all models

---
## Problem Statement
Sleep disorders like Insomnia and Sleep Apnea significantly impact an individual's physical and mental well-being. Early detection of such conditions can help improve lifestyle interventions, prevent chronic illness, and optimize overall health.

This project aims to develop a machine learning and deep learning-based classification system to predict sleep disorders using features like:

Sleep Duration and Quality
Stress and Physical Activity Levels
Heart Rate, Daily Steps
BMI Category, Occupation, and more
By analyzing patterns in health and lifestyle indicators, we aim to accurately classify whether an individual is likely to suffer from Insomnia or Sleep Apnea.

The goal is to:

Identify key indicators of sleep disorders
Build interpretable and accurate models
Compare multiple ML and DL algorithms

---
#  Conclusion
Through comprehensive EDA and model training:

- We visualized strong relationships between stress, activity level, BMI, and sleep disorders.
- Multiple machine learning models (e.g., Random Forest, Gradient Boosting, Logistic Regression) were trained and evaluated.
- A deep learning model using Keras was also built and showed competitive performance.
- The best models achieved high accuracy in classifying Sleep Apnea vs Insomnia cases.
This analysis demonstrates the potential of AI-powered approaches in automating early detection of sleep disorders, which could assist healthcare professionals in preventive diagnosis and lifestyle planning.
---
## Accuracy Comparison of ML & DL Models
<img width="1459" height="567" alt="image" src="https://github.com/user-attachments/assets/457837c7-d34d-470f-849b-1fad8be4c645" />

---
##  Dataset
Includes features like:
- Sleep Duration, Stress Level, Physical Activity
- BMI, Heart Rate, Daily Steps
- Target: Sleep Disorder (binary)

---

##  How to Use
```bash
git clone https://github.com/your-username/sleep-disorder-ml-dl.git
cd sleep-disorder-ml-dl
jupyter notebook sleep-disorder-prediction-using-ml-dl.ipynb

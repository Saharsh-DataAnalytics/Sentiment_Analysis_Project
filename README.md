# 📊 Amazon Customer Review Sentiment Analysis

> **CodeAlpha Data Analytics Internship - Task 4**

A complete end-to-end **Natural Language Processing (NLP)** project that analyzes Amazon customer reviews to classify customer sentiment into **Positive**, **Negative**, and **Neutral** categories using **TF-IDF Vectorization** and **Logistic Regression**. The project also generates meaningful business insights to help organizations understand customer opinions and improve product quality.

---

# 📌 Project Overview

Customer reviews play a crucial role in understanding customer satisfaction and product performance. However, manually analyzing thousands of reviews is time-consuming and impractical.

This project uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to automatically analyze customer reviews and classify their sentiment. In addition to sentiment prediction, the project identifies frequently discussed product-related words and provides business recommendations based on customer feedback.

---

# 🎯 Business Problem

Amazon receives thousands of customer reviews every day across different product categories. These reviews contain valuable information about customer satisfaction, product quality, and recurring issues. However, manually analyzing such a large volume of textual data is inefficient and difficult.

Businesses need an automated solution that can classify customer reviews into meaningful sentiment categories and identify common customer concerns to support data-driven decision-making.

---

# 🎯 Business Objective

The main objectives of this project are:

- Classify customer reviews into Positive, Negative, and Neutral sentiments.
- Analyze overall customer satisfaction.
- Identify the most frequently discussed product features.
- Detect recurring customer complaints.
- Build and evaluate a Machine Learning model for sentiment prediction.
- Generate actionable business insights and recommendations.

---

# 📂 Dataset Information

**Dataset:** Amazon Electronics Reviews Dataset

The dataset contains customer reviews for electronic products available on Amazon.

### Important Columns

- Review Text
- Review Summary
- Overall Rating
- Product ID
- Reviewer Name
- Review Date

### Sentiment Labels

| Rating | Sentiment |
|---------|-----------|
| 1 – 2 | Negative |
| 3 | Neutral |
| 4 – 5 | Positive |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- WordCloud
- NLTK
- Jupyter Notebook

---

# 🧠 NLP Techniques Used

- Text Cleaning
- Lowercase Conversion
- Punctuation Removal
- Stopword Removal
- Tokenization
- Bag of Words (BoW)
- TF-IDF Vectorization

---

# 🤖 Machine Learning Model

**Model Used**

- Logistic Regression

### Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report

---

# 📈 Project Workflow

```text
Load Dataset
      │
      ▼
Understand Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Text Preprocessing
      │
      ▼
Bag of Words
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Train-Test Split
      │
      ▼
Logistic Regression
      │
      ▼
Model Evaluation
      │
      ▼
Business Insights
      │
      ▼
Business Recommendations
```

---

# 📊 Visualizations

The project includes the following visualizations:

- Customer Sentiment Distribution
- Confusion Matrix
- Classification Report
- Top 10 Positive Words
- Top 10 Negative Words
- Positive Word Cloud
- Negative Word Cloud

---

# 🔍 Key Findings

- Approximately **79.8%** of customer reviews were classified as **Positive**, indicating a high level of customer satisfaction.

- Logistic Regression achieved an accuracy of approximately **82.4%**, demonstrating effective sentiment classification.

- Positive reviews were largely focused on overall product satisfaction and customer experience.

- Negative reviews frequently included complaint-related words such as **problem**, **unit**, and **not**, highlighting recurring customer issues.

- Word frequency analysis and Word Clouds helped identify commonly discussed terms in both positive and negative customer feedback.

---

# 💡 Business Recommendations

- Continue maintaining the product quality that customers appreciate.

- Investigate recurring customer complaints to identify the root causes of dissatisfaction.

- Strengthen product quality assurance before shipment.

- Monitor customer sentiment regularly to identify emerging product issues.

- Use positive customer feedback in marketing campaigns while using negative feedback to guide product improvements.

---

# 📁 Repository Structure

```text
Sentiment_Analysis_Project
│
├── Dataset
│   └── Amazon Reviews Dataset
│
├── Images
│   ├── Sentiment Distribution
│   ├── Confusion Matrix
│   ├── Classification Report
│   ├── Positive Words
│   ├── Negative Words
│   ├── Positive Word Cloud
│   └── Negative Word Cloud
│
├── Notebook
│   └── Sentiment_Analysis.ipynb
│
├── Report
│   └── Sentiment Analysis Report.pdf
│
├── requirements.txt
│
└── README.md
```

---


# 📚 Future Improvements

- Improve Neutral sentiment prediction using class balancing techniques.
- Experiment with advanced Machine Learning models such as Random Forest and XGBoost.
- Implement Deep Learning models such as LSTM and BERT.
- Perform Aspect-Based Sentiment Analysis.
- Deploy the model as an interactive web application using Streamlit.

---

# 👨‍💻 Author

**Saharsh Anant Sarde**

Computer Engineering Student | Aspiring Data Analyst

GitHub:
https://github.com/Saharsh-DataAnalytics

LinkedIn:
https://www.linkedin.com/in/saharsh-sarde-1706782a8

---

# ⭐ If you found this project useful, consider giving it a Star!

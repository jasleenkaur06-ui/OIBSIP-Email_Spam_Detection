# AICTE OIBSIP – Task 4: Email Spam Detection using Machine Learning

## 📌 Project Overview

This project is submitted as **Task 4** of the **AICTE Oasis Infobyte (OIBSIP) Internship Program**. The objective is to develop an **Email Spam Detection System** using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The system classifies incoming messages into **Spam** (unwanted messages) or **Ham** (legitimate messages).

The project demonstrates the complete machine learning workflow, including data preprocessing, feature extraction, model training, evaluation, and visualization.

---

## 🎯 Objectives

* Load and explore the spam dataset.
* Analyze the distribution of spam and ham messages.
* Perform text preprocessing using NLP techniques.
* Convert text into numerical features using TF-IDF Vectorization.
* Train multiple machine learning classification models.
* Evaluate model performance using standard metrics.
* Visualize the results with graphs and WordClouds.
* Compare the performance of different classifiers.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* NLTK
* Scikit-learn
* WordCloud

---

## 📂 Dataset

**Dataset:** SMS Spam Collection Dataset

The dataset consists of SMS messages labeled as:

* **Ham** – Legitimate messages
* **Spam** – Unwanted, promotional, or fraudulent messages

Dataset File:

```text
spam.csv
```

---

## 🔄 Project Workflow

### 1. Data Loading

* Load the dataset using Pandas.
* Display dataset information.
* Check dataset dimensions.
* Rename columns.
* Remove unnecessary columns.

### 2. Data Cleaning

* Check for missing values.
* Remove duplicate records.
* Verify dataset consistency.

### 3. Exploratory Data Analysis

* Display spam and ham message counts.
* Calculate class percentages.
* Visualize class distribution using a bar chart.

### 4. Text Preprocessing

The following preprocessing steps were applied:

* Convert text to lowercase.
* Remove punctuation.
* Remove numbers.
* Remove stopwords.
* Apply Porter Stemming.

### 5. Feature Extraction

The cleaned messages were converted into numerical vectors using the **TF-IDF (Term Frequency–Inverse Document Frequency) Vectorizer**, which assigns higher importance to words that are significant within a message while reducing the weight of commonly occurring words.

### 6. Train-Test Split

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

### 7. Machine Learning Models

The following models were trained and compared:

* **Multinomial Naive Bayes**
* **Logistic Regression**

---

## 📊 Model Evaluation

The models were evaluated using the following performance metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

---

## 📈 Visualizations Included

* Spam vs. Ham Distribution Graph
* Confusion Matrix (Multinomial Naive Bayes)
* Confusion Matrix (Logistic Regression)
* Model Accuracy Comparison Graph
* Performance Comparison Chart
* Spam WordCloud
* Ham WordCloud

---

## 📋 Results

Both machine learning models successfully classified spam and legitimate messages.

The performance comparison based on Accuracy, Precision, Recall, and F1-Score helps identify the most effective classifier for spam detection. The results demonstrate that TF-IDF combined with machine learning provides an efficient solution for detecting spam messages.

---

## 💡 Importance of Recall

Recall measures the percentage of actual spam messages that are correctly identified by the model.

A high recall is particularly important because it minimizes the number of spam messages that are incorrectly classified as legitimate, reducing the risk of phishing, scams, and unwanted content reaching users.

---

## 🚀 Future Enhancements

* Train on larger email datasets.
* Implement Support Vector Machine (SVM).
* Apply Lemmatization instead of Stemming.
* Use Deep Learning models such as LSTM or BERT.
* Deploy the model using Flask or Streamlit.
* Develop a real-time web-based spam detection application.

---

## 📁 Project Structure

```text
AICTE-OIBSIP-Task4-Email-Spam-Detection/
│
├── Email_Spam_Detection.ipynb
├── spam.csv
├── README.md
├── requirements.txt
└── images/
```

---

## 📚 Libraries Used

* pandas
* numpy
* matplotlib
* nltk
* scikit-learn
* wordcloud

---

## ▶️ How to Run the Project

1. Download or clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all cells in sequence.
5. View the evaluation metrics, visualizations, and model comparison.

---

## 🏆 Conclusion

This project successfully demonstrates the use of **Natural Language Processing (NLP)** and **Machine Learning** for spam message classification. Through text preprocessing and TF-IDF feature extraction, meaningful textual features were extracted for model training. Both **Multinomial Naive Bayes** and **Logistic Regression** achieved strong performance, with the better-performing model identified based on evaluation metrics. The project highlights the effectiveness of machine learning techniques in automatically filtering spam messages and improving communication security.

---

## 👩‍💻 Author

**Jasleen Kaur**

**AICTE Oasis Infobyte (OIBSIP) Internship – Task 4**

# Email Spam Detection using Machine Learning – OIBSIP Task 4

## Objective

The objective of this project is to build a machine learning model that can classify emails as **spam** or **not spam** based on their content. This task focuses on using **Natural Language Processing (NLP)** techniques combined with supervised ML algorithms to automate spam detection and improve email filtering systems.

---

## Steps Performed

1. **Data Collection**
   - Loaded a labeled dataset containing email messages and their classification (`spam` or `ham`).

2. **Data Preprocessing**
   - Converted all text to lowercase.
   - Removed punctuation, stopwords, and special characters.
   - Applied stemming using **NLTK’s PorterStemmer**.
   - Transformed text into numerical vectors using **CountVectorizer** (Bag of Words).

3. **Model Building**
   - Trained two classification models:
     - **Multinomial Naive Bayes**
     - **Logistic Regression**

4. **Model Evaluation**
   - Evaluated using metrics like **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**.
   - Compared the performance of models visually using plots.

---

## Tools & Technologies Used

- **Python** 
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **NLTK** – natural language preprocessing
- **Sklearn (Scikit-learn)** – model training and evaluation
- **Matplotlib** & **Seaborn** – data visualization

---

## Outcome

- Successfully trained models that classify emails with high accuracy.
- Identified Logistic Regression and Naive Bayes as effective models for text classification.
- Gained practical experience in applying NLP techniques and evaluating classification models.

---

## Acknowledgment

This project was developed as part of the **Oasis Infobyte Internship Program (OIBSIP)** for the **Data Science Domain**.

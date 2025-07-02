# 📰 News Article Classification

## 📌 Overview

In an era where digital content is continuously growing, classifying news articles into categories like **Sports**, **Politics**, and **Technology** helps media platforms streamline content delivery and enhance user experience. This project aims to develop a machine learning model to **automatically classify news articles** based on their textual content.

By automating this classification process, organizations can significantly improve their **content management systems**, **recommendation engines**, and **reader engagement**.

---

## 🎯 Problem Statement

The primary objective of this project is to build a **text classification model** that can automatically categorize news articles into **predefined categories**. The model is trained on a labeled dataset and outputs the **most likely category** (e.g., *sports*, *politics*, or *technology*) for each input article.

### Key Goals:
- Preprocess and clean raw text data.
- Extract features using NLP techniques.
- Build and evaluate classification models.
- Draw insights and visualize performance.

---

## 🗂️ Dataset Information

- **Dataset Name**: [`data_news`](https://docs.google.com/spreadsheets/d/1m4YMfqQxo_DcbtzGqbfZitvJmytbWUE8qjixhHmtadk/edit?usp=sharing)
- **Features**:
  - `text`: The full content of the news article.
  - `category`: The corresponding label/category (e.g., sports, politics, technology).

---

## ✅ Deliverables

### 1. 📂 Data Collection and Preprocessing
- Clean raw text: remove punctuation, stopwords, special characters.
- Perform tokenization and lowercasing.
- Handle missing values and null records.
- Prepare the data for modeling.

### 2. ✨ Feature Extraction
- Convert text to numerical features using:
  - **TF-IDF**
  - **Bag-of-Words**
  - **Word2Vec or GloVe** (optional)
- Conduct **exploratory data analysis (EDA)** to:
  - Check class balance
  - Visualize keyword frequency by category
![image](https://github.com/user-attachments/assets/a285ca73-8f3b-4407-b05c-b35011d97a58)


![image](https://github.com/user-attachments/assets/73afb967-8efd-425f-9bcf-d8c4d554c1a3)


![image](https://github.com/user-attachments/assets/bd9224d5-243f-46d8-9025-61b5e61831b9)


![image](https://github.com/user-attachments/assets/63d722e4-a030-4d55-b513-59eb99fd2bc9)

![image](https://github.com/user-attachments/assets/253849d5-13fa-4a04-82ef-839249f31329)


### 3. ⚙️ Model Development and Training
- Build classification models using:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machines (SVM)
- Train and validate models using **cross-validation** and **hyperparameter tuning**

### 4. 📏 Model Evaluation
- Evaluate models using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
- Compare performance to select the best classifier.

### 5. 🎥 Final Report and Presentation
- Create a report summarizing:
  - Data processing
  - Modeling pipeline
  - Results & insights
  - Techniques used
  - Final outcomes
- Include:
  - Visualizations (bar charts, confusion matrix, feature importance)
  - Google Drive link to the video in the notebook/report

---

## 🛠️ Tools & Technologies

- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `nltk`, `spaCy` – NLP preprocessing
  - `scikit-learn` – Machine learning
  - `matplotlib`, `seaborn` – Data visualization
- **Notebook**: Jupyter Notebook (.ipynb)

---

## 📊 Visualizations Used

- Category distribution bar chart
- Word cloud by category
- Confusion matrix
- Precision-Recall curves

---

## 🙋 Author

**Rahul Yadav**  
Aspiring Data Scientist | NLP & AI Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/rahulyadav2707/) 



# 📧 Email Spam Detection with Machine Learning  

## 📌 Project Overview  
This project builds a **machine learning model** to classify emails as **spam or ham (not spam)** using **Natural Language Processing (NLP)** techniques. It leverages **TF-IDF vectorization** for feature extraction and **Multinomial Naïve Bayes (MNB)** for classification.  

## 🚀 Features  
✔️ Preprocesses text by **removing stopwords, lemmatizing words, and cleaning text**.  
✔️ Extracts important words using **TF-IDF vectorization**.  
✔️ Trains a **Multinomial Naïve Bayes (MNB) classifier**.  
✔️ Evaluates model performance using **accuracy and classification reports**.  
✔️ Provides **data visualizations** like **word clouds** and **feature importance graphs**.  

## 🗂 Dataset  
The dataset (`spam.csv`) contains **emails labeled as "spam" or "ham"**:  
- **v1** → Label (`ham` or `spam`, converted to `0` or `1`).  
- **v2** → Email message content.  

## 🛠 Technologies Used  
🔹 Python 🐍  
🔹 Pandas & NumPy (Data Processing)  
🔹 Scikit-Learn (Machine Learning)  
🔹 NLTK (Text Processing)  
🔹 Matplotlib & Seaborn (Visualization)  
🔹 WordCloud (Text Analysis)  

## 🏗 Model Training & Evaluation  

### 1️⃣ Data Preprocessing  
- Convert text to **lowercase**.  
- Remove **special characters** and **stopwords**.  
- Apply **lemmatization**.  

### 2️⃣ Feature Extraction  
- Used **TF-IDF vectorization** (top 5000 words).  

### 3️⃣ Model Training  
- Used **Multinomial Naïve Bayes (MNB)**.  
- Split data into **80% training, 20% testing**.  

### 4️⃣ Performance Metrics  
- **Accuracy**: `xx%` *(update this with actual accuracy from your notebook)*  
- **Classification Report**: *(Precision, Recall, F1-score, etc.)*  

---

## 📊 Visualizations  
📌 **Spam vs. Ham Distribution** (Bar Plot)  
📌 **Word Clouds** for spam and ham messages  
📌 **Top 20 Words by TF-IDF Score** (Bar Plot)  

---

## 🤝 Contributing  
Feel free to submit **pull requests** or report issues!  

---

## 📜 License  
This project is licensed under the **MIT License**.  


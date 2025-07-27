# DATA_SCIENCE
# 🛡️ Phishing Website Prediction Model

This project uses **Machine Learning** and **Natural Language Processing (NLP)** techniques to detect **phishing websites** based on URL analysis. It aims to help users stay protected from cyber threats by enabling real-time and automated phishing detection.

---

## 📘 Abstract

This solution classifies website URLs as either **legitimate ("good")** or **malicious ("bad")**. By leveraging supervised learning models such as **Logistic Regression** and **Multinomial Naive Bayes**, we have built a pipeline that delivers high accuracy and can be deployed for real-time detection tasks.

---

## 🎯 Objective

To build an **automated and scalable system** that can classify phishing websites using:
- NLP techniques for URL feature extraction
- Supervised ML algorithms for classification
- Modular pipelines for deployment and interpretation

---

## 🧠 Motivation

Phishing attacks are **increasingly sophisticated** and often bypass traditional blacklist-based systems. Manual detection is **slow and inaccurate**, motivating the need for an intelligent, real-time solution.

---

## ❌ Existing Problems

- Dependence on outdated blacklists  
- High false-positive rates  
- Inability to detect new phishing patterns quickly  

---

## ✅ Proposed Solution

- ML-based classification using **Logistic Regression** and **Multinomial Naive Bayes**
- Preprocessing steps: **Tokenization, Stemming, Feature Extraction**
- Visualizations: **Word Clouds**, **Confusion Matrix**, Performance Metrics
- Deployment-ready pipeline using **pickle**

---

## 🛠️ Technologies Used

| Category      | Tools & Libraries                        |
|---------------|------------------------------------------|
| Programming   | Python                                   |
| NLP           | NLTK (tokenization, stemming)            |
| ML            | scikit-learn (vectorization, modeling)   |
| Visualization | matplotlib, seaborn, WordCloud           |
| Persistence   | pickle                                   |
| Platform      | Jupyter Notebook / any Python IDE        |

---

## 🧱 System Architecture

1. **Data Preprocessing**  
   - Clean and tokenize URLs  
   - Apply stemming  
   - Convert text to vectors (Bag-of-Words / TF-IDF)

2. **Model Development**  
   - Train using **Logistic Regression** and **Naive Bayes**
   - Create a complete ML pipeline

3. **Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1-Score  
   - Visualizations: Word Clouds, Confusion Matrix

4. **Deployment**  
   - Save model using `pickle`  
   - Load and use for real-time predictions

---

## 📊 Results

| Metric                  | Logistic Regression | Multinomial Naive Bayes |
|-------------------------|---------------------|--------------------------|
| Accuracy                | 96.4%               | 95.8%                    |
| Precision, Recall, F1   | High across all     | High across all          |

- Word clouds reveal frequent tokens in good vs. bad URLs  
- Clear visual output using matplotlib and seaborn

---

## 🔚 Conclusion

- This project presents a **robust, automated** phishing detection model  
- Strong performance with basic ML models and URL-based features  
- Demonstrates the power of **NLP + ML in cyber threat detection**

### 🚧 Limitations
- Heavily dependent on labeled training data  
- May underperform on unseen or highly obfuscated URLs  

### 🔮 Future Work
- Expand dataset diversity  
- Try deep learning models (e.g., LSTMs, CNNs on text)  
- Build a real-time API for production use  

---

## 📁 Repository Structure

| File                    | Description                                 |
|-------------------------|---------------------------------------------|
| `presentation.pptx`     | PowerPoint summarizing the entire project   |
| `phishing_model.pkl`    | Saved pipeline model (if available)         |
| `notebook.ipynb`        | Jupyter Notebook with code and outputs      |
| `requirements.txt`      | Python dependencies                         |

---

## 👥 Authors

- Sparsh Garg [RA2211003030192]  
- Arpit Singhal [RA2211003030197]

Submitted to: **Ms. Madhuri Sharma**

---

## 📬 Contact

Feel free to connect or collaborate:

📧 Email: [arpitsinghal00001@gmail.com](mailto:arpitsinghal00001@gmail.com)  
🔗 LinkedIn: [Arpit Singhal](https://www.linkedin.com/in/arpitsinghal22102003/)

---

🛡️ _Protecting users, one URL at a time._

# 📊 Hilton Hotel London - Sentiment Analysis Project

## 🎯 Project Overview
- **Objective:** Analyze customer reviews for Hilton Hotels in London to identify key areas of dissatisfaction and improve guest experience.
- **Approach:** Perform **sentiment analysis** on reviews using NLP techniques and build a predictive model to classify future reviews.
- **Outcome:** Generate insights for hotel management and deploy a **sentiment classification tool**.

## 🔍 Dataset Used
- **Source:** Tripadvisor hotel reviews dataset (scraped data)
- **Attributes:** Hotel Name, Review Summary, Review Text, Score (1-5 Bubble Ratings)
- **Size:** 17,537 reviews (after cleaning)

## 🛠 Technologies Used
- **Data Processing:** Python (Pandas, NumPy, Regex, NLTK)
- **Visualization:** Matplotlib, Seaborn, WordCloud
- **Machine Learning Models:** Logistic Regression, Random Forest, Support Vector Machine (SVM), BERT
- **Feature Engineering:** Bag-of-Words (BoW), TF-IDF, Word2Vec
- **Sentiment Analysis:** VADER, ML models
- **Deployment Tools:** Flask (Optional Future Scope)

## 📊 Exploratory Data Analysis (EDA)
- **Numeric Score Distribution:** Majority of reviews have positive scores (40-50), but there are key areas of dissatisfaction (10-20 scores).
- **Hotel-Specific Sentiment Trends:** Hilton London Metropole and Hilton London Gatwick Airport had the most **mixed reviews**.
- **Word Frequency Analysis:** Positive reviews emphasized **“location,” “lounge,” and “breakfast”**, while negative reviews mentioned **“dirty,” “check-in,” and “staff”** frequently.

## 📌 Sentiment Classification Models
1️⃣ **Baseline Model:** VADER (Lexicon-based Sentiment Analysis) - **76% accuracy**
2️⃣ **Machine Learning Models:**
   - **Logistic Regression (TF-IDF)** – Best model with **87% accuracy**
   - **Random Forest (TF-IDF)** – Slightly lower performance at **84% accuracy**
   - **SVM (TF-IDF)** – Achieved **86% accuracy**, close to Logistic Regression
3️⃣ **Deep Learning Model:** BERT (Transformers-based NLP model) - **86.6% accuracy**, but computationally expensive

## 🔥 Key Insights & Recommendations
- **Room Cleanliness & Comfort:** Frequent complaints about **dirty rooms, old furniture, and lack of maintenance**.
- **Check-in & Service Delays:** Long waiting times at **reception and unfriendly staff experiences**.
- **Pricing Concerns:** Overpriced food, expensive stays without added value.
- **Improvement Strategy:**
  - Enhance **cleaning protocols** and **room renovations**
  - Implement **staff training programs** to improve guest interactions
  - Reassess **pricing strategies** and add more **value-based offerings**

## 🚀 How to Run This Project
1️⃣ **Clone the repository:**
```bash
   git clone https://github.com/yourgithub/hilton-sentiment-analysis.git
```
2️⃣ **Install dependencies:**
```bash
   pip install -r requirements.txt
```
3️⃣ **Run sentiment analysis:**
```bash
   python sentiment_analysis.py
```
4️⃣ **Explore Data & Insights:**
   - Open **Jupyter Notebook** to explore EDA and model training steps.
   - Load the **Power BI/Tableau Dashboard** for interactive visualization.

## 📸 Sample Visualizations
![image](https://github.com/user-attachments/assets/75bde8fb-9a07-40a1-8739-f084f42e1bf2)


## 📫 Connect With Me
🔗 LinkedIn: [https://www.linkedin.com/in/harishkd](https://www.linkedin.com/in/harishkd)  
📧 Email: [harishkumard97@gmail.com](mailto:harishkumard97@gmail.com)

---
## ⚠️ Disclaimer
This project is intended for **educational and practice purposes only**. The dataset used is publicly available, and **no confidential or proprietary information is included**. The analysis and models built do not reflect any official Hilton policies or operations. **I am not liable for any consequences arising from the use of this project.**

🚀 *This project highlights the power of sentiment analysis in improving customer experiences! Feel free to explore and contribute!*


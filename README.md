# 📊 Hilton Hotel Reviews - Sentiment Analysis

**Project Focus:** Applying Natural Language Processing (NLP) and Machine Learning to analyze Hilton Hotel customer reviews, identify key drivers of guest satisfaction, and build a high-accuracy sentiment classification model.

---

## 🌟 Executive Summary

This project transforms unstructured customer feedback into actionable business intelligence. By analyzing over 17,000 hotel reviews, we identified critical service areas and developed a model to automate the classification of future reviews, enabling management to proactively address guest concerns.

| Business Problem | Technical Solution | Key Result |
| :--- | :--- | :--- |
| Inability to quantify key themes from thousands of text reviews. | **NLP with TF-IDF and Machine Learning models.** | **Logistic Regression** model achieved **87% accuracy** in classifying review sentiment. |

---

## 🛠️ Technical Skills & Technologies

This project demonstrates a comprehensive skillset in data science, from initial data processing and NLP to model development and evaluation.

| Area | Technologies & Techniques |
| :--- | :--- |
| **Languages & Libraries** | Python (Pandas, NumPy, NLTK, Scikit-learn) |
| **Data Analysis** | Exploratory Data Analysis (EDA), Text Preprocessing (Regex, Tokenization, Stopwords) |
| **NLP Feature Engineering** | Bag-of-Words (BoW), **TF-IDF (Top Performer)**, Word2Vec |
| **Modeling** | **Logistic Regression (Selected)**, Random Forest, SVM, BERT |
| **Visualization** | Matplotlib, Seaborn, WordCloud |

---

## 💡 Top 3 Actionable Insights

The analysis revealed specific, recurring themes in guest feedback that directly impact satisfaction scores.

| Key Driver | Common Feedback | Business Recommendation |
| :--- | :--- | :--- |
| **1. Service Quality** | "check-in," "staff," "rude" | Implement targeted staff training programs focused on improving front-desk efficiency and guest interaction protocols. |
| **2. Room Condition** | "dirty," "old," "small" | Prioritize a budget for room renovations and enhance housekeeping quality assurance checks. |
| **3. Positive Drivers** | "location," "breakfast," "lounge" | Leverage these strengths in marketing campaigns to highlight key differentiators and attract new guests. |

---

## 🏆 Model Performance & Selection

Multiple models were evaluated to find the best balance of performance and efficiency. The **Logistic Regression** model using TF-IDF features was selected as the optimal solution.

| Model | Feature Engineering | Accuracy |
| :--- | :--- | :--- |
| Baseline: VADER | Lexicon-based | 76.0% |
| **Final: Logistic Regression** | **TF-IDF** | **87.0%** |
| Support Vector Machine (SVM) | TF-IDF | 86.0% |
| BERT (Deep Learning) | Transformers | 86.6% |
| Random Forest | TF-IDF | 84.0% |

---

## 💻 Project Walkthrough

The complete analysis, including data cleaning, exploratory visualizations, and model training, is documented in the accompanying Jupyter Notebook.

### How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/harris97/hilton-sentiment-analysis.git](https://github.com/harris97/hilton-sentiment-analysis.git)
    cd hilton-sentiment-analysis
    ```
2.  **Install the required dependencies:** (You may need to add `nltk` libraries as prompted in the notebook)
    ```bash
    pip install pandas numpy matplotlib seaborn wordcloud scikit-learn nltk
    ```
3.  **Launch Jupyter and run the notebook:**
    ```bash
    jupyter notebook Harish_Individual_Project.ipynb
    ```

---
## 📫 Connect With Me

* **LinkedIn:** [https://www.linkedin.com/in/harishkd](https://www.linkedin.com/in/harishkd)
* **Email:** [harishkumard97@gmail.com](mailto:harishkumard97@gmail.com)

# 📱 Educational App Usability and Sentiment Analysis

This project explores user perceptions of mobile learning platforms by analyzing thousands of real user reviews from the Google Play Store. The aim is to identify patterns in sentiment and usability of educational applications using machine learning classification models.

## 🎯 Objective

To investigate public perception and effectiveness of educational apps using supervised learning techniques and sentiment analysis. The project seeks to understand how users experience learning via mobile platforms and what factors drive positive or negative feedback.

## 🧪 Methodology

### 🔹 Data Collection
- 10,494 user reviews were manually scraped and labeled from educational apps on the Google Play Store.
- Each review was categorized into one of three classes: **Positive**, **Negative**, or **Neutral**.

### 🔹 Preprocessing
- Text cleaning and normalization (removal of null values, encoding labels, formatting for models)
- Tokenization and numerical representation where needed

### 🔹 Models Applied
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Gaussian Naive Bayes**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Classifier (SVC)**
- **XGBoost**

Each model was trained on 80% of the dataset and tested on the remaining 20%.

## 📊 Evaluation Metrics

We used the following metrics for evaluation:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

> Notably, models such as **KNN, Decision Tree, Random Forest, and XGBoost** achieved over 99% accuracy, with XGBoost reaching **100%** accuracy on the test set.

## 📈 Results

| Algorithm        | Accuracy | Best Feature |
|------------------|----------|--------------|
| Logistic Regression | 97%      | High recall |
| KNN               | 99%      | Low false positives |
| Decision Tree     | 99%      | Balanced precision and recall |
| Random Forest     | 99%      | Robust performance |
| SVC               | 99%      | Consistent F1-score |
| XGBoost           | **100%** | Best overall |

## 📌 Key Insights

- Educational apps are largely positively reviewed, but **usability issues** and **technical limitations** still exist.
- Public sentiment aligns with the **Technology Acceptance Model (TAM)** concepts like perceived usefulness and ease of use.
- Supervised learning models are highly effective in classifying opinion-based data in the educational technology domain.

## 🧠 Tools & Technologies

- **Python 3.x**
- **Scikit-learn**
- **pandas, NumPy, matplotlib**
- **Jupyter Notebook**
- **Manual annotation and preprocessing**

## 📄 Documentation

- [Research Paper (PDF)](./Supervised%20Method%20Pursued%20For%20Cogitation%20regarding%20educational%20application.pdf) – a comprehensive write-up of the methodology, experiments, and results.

## 🧩 Future Work

- Extend data to include app usage statistics and more qualitative feedback
- Use topic modeling (e.g., LDA) to explore thematic patterns in app reviews
- Collaborate with educational researchers to refine analysis frameworks
- Apply meta-analytical techniques on similar app review studies

## 👨‍💻 Author

**Md. Touhidur Rahman**  
M.Sc. Data Science Student, Friedrich-Alexander-Universität Erlangen-Nürnberg  
[GitHub](https://github.com/md-touhidur-rahman) • [LinkedIn](https://www.linkedin.com/in/mdtouhidur/) • [Email](mailto:touhid129@gmail.com)

---

_This project is intended for academic and research purposes in the fields of educational technology, machine learning, and applied data science._

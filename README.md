## 💡 Introduction

This project analyzes and identifies duplicate question pairs on Quora using advanced natural language processing (NLP) and machine learning techniques. The goal is to determine if two questions have the same intent, thereby helping Quora improve its user experience by avoiding redundant content.

---

## ✨ Features

- **Data Preprocessing**: Handles text cleaning, stemming, and lemmatization.
- **Exploratory Data Analysis (EDA)**: Visualizes the data distribution, question lengths, and more.
- **Feature Engineering**: Generates word embeddings, TF-IDF features, and similarity measures.
- **Model Training**: Implements ML models like Random Forest (Gini & Log-loss), XGBoost.
- **Evaluation**: Uses metrics such as F1 Score, Precision, Recall, and ROC-AUC (Max accuracy is 83%).
- **Deployment**: Ready for integration into web applications or API services.

---

## 📊 Dataset

The dataset is sourced from the [Kaggle Quora Duplicate Questions dataset](https://www.kaggle.com/c/quora-question-pairs). It consists of:

- **Train.csv**: Contains pairs of questions labeled as duplicate or not.
- **Test.csv**: Contains question pairs for prediction (labels are hidden).


## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Commit your changes.
4. Submit a pull request.

## 🌟 Acknowledgments

- [Kaggle Quora Question Pairs Dataset](https://www.kaggle.com/c/quora-question-pairs)
- [Scikit-learn](https://scikit-learn.org/)
- [NLTK](https://www.nltk.org/)
- [XGBoost](https://xgboost.readthedocs.io/)

The working directory is too huge to push on GitHub thus only app.ipynb is pushed, you can look through that file and get the intuition of the project. You can try to run that file with some smaller data to create your own app. 

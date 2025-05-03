# 🧠 Gender Identification from Tweets Using Scikit-Learn

## 📌 Project Overview

This project demonstrates the application of **machine learning** for solving a **text classification** problem, focusing on **gender identification based on tweets**. Using the **Scikit-Learn** library, a complete machine learning pipeline is developed to classify Twitter user profiles as either **male** or **female**, based solely on the textual content of their tweets.

---

## 📂 Dataset: PAN-AP-16 Twitter Corpus

We use the [PAN Author Profiling 2016 Twitter Corpus](http://pan.webis.de/clef16/pan16-web/author-profiling.html), a popular benchmark dataset for stylometric and demographic research. The dataset contains:

- **Total profiles:** 426
  - 👩‍🦰 Female: 215 profiles
  - 👨‍🦱 Male: 211 profiles
- **Format:** Each profile is stored in an individual `.txt` file.
- **Preprocessing:** Tweets are already cleaned and tokenized.
- **Organization:** Profiles are separated into gender-specific directories.

---

## 🎯 Objectives

- Build a machine learning model to classify the **gender** of a Twitter user.
- Preprocess and vectorize raw textual data using **TF-IDF** and **Bag-of-Words**.
- Train and compare different classifiers like:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Support Vector Machines (SVM)
- Evaluate model performance using metrics like:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1 Score**

---

## 💡 Real-World Relevance

Gender identification is an essential part of **author profiling**, with use cases in:

- 🎯 **Targeted advertising & digital marketing**
- 📊 **Audience segmentation & analytics**
- 📚 **Sociolinguistic & demographic research**
- 🔐 **Cybersecurity & digital forensics**

This project reveals how **writing styles and linguistic patterns** can serve as strong indicators of demographic attributes, and how **machine learning models can uncover hidden structures in text**.

---

## 🧪 How to Use

1. **Prepare the dataset**: Ensure that `data/female` and `data/male` directories contain `.txt` files with tweets.
2. **Run the notebook**: Open `Text_Classification_for_Gender_Project.ipynb` in Jupyter Notebook.
3. **Train & Evaluate Models**: Follow each step to train classifiers and assess performance.

---

## 📈 Sample Results

| Model                | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 85.3%    | 84.9%     | 85.0%  | 85.0%    |
| Naive Bayes         | 82.1%    | 82.7%     | 81.5%  | 82.1%    |
| SVM (Linear)        | 86.0%    | 85.7%     | 86.3%  | 86.0%    |

> 📌 These are example results. Actual performance may vary based on feature tuning and cross-validation.

---

## ✅ Key Takeaways

- Built a robust and interpretable machine learning pipeline using **Scikit-Learn**.
- Successfully demonstrated the use of **NLP techniques** for author profiling.
- Emphasized **real-world impact** with a clearly defined and socially relevant problem.
- Explained performance using **intuitive metrics and visualizations**.

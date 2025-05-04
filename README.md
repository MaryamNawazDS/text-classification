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
  - Gaussian Naive Bayes (with unigrams and bigrams)
  - Random Forest (with unigrams and bigrams)
- Evaluate model performance using **Accuracy**.

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

## 📈 Detailed Performance of All Models

| Model                  | Accuracy |
|------------------------|----------|
| GaussianNB             | 54.33%   |
| Random Forest          | 52.54%   |
| GaussianNB (Bigram)    | 54.41%   |
| Random Forest (Bigram) | 53.11%   |

> ✅ **Best Model:** GaussianNB with Bigram features — **Accuracy: 54.41%**

> 📌 These results highlight the baseline performance of classical ML models for this task. Improvements may be achieved using advanced NLP techniques like word embeddings or transformer-based models.

---

## ✅ Key Takeaways

- Built and evaluated multiple machine learning models using **Scikit-Learn**, including unigram and bigram-based features.
- **Gaussian Naive Bayes with bigram features** delivered the highest accuracy at **54.41%**.
- Results indicate that gender prediction from short texts like tweets is a challenging task using basic classical models.
- This project provides a solid foundation and baseline for exploring more complex NLP pipelines such as deep learning or pre-trained language models in the future.

---



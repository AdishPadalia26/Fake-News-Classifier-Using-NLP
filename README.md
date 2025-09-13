# 📰 Fake-News-Classifier-Using-NLP 🚫

## ✨ Overview

Welcome to the **Fake News Classifier** repository! This project demonstrates how to detect fake news articles using Natural Language Processing (NLP) and Machine Learning techniques. Explore, learn, and compare multiple approaches to battle misinformation! ⚔️

---

## 📁 Project Structure

```
Fake-News-Classifier-Using-NLP/
│
├── Fake News Classifier using SVM.ipynb
├── Fake News Classifier using Bag of words.ipynb
├── Fake News Classifier using TFIDF.ipynb
├── fake-news/
│   ├── train.csv
│   ├── test.csv
│   └── submit.csv
└── README.md
```

---

## 🧠 Approaches

### 🕵️‍♂️ SVM Classifier
*Notebook: `Fake News Classifier using SVM.ipynb`*

- ➡️ **Feature Extraction**: (Bag of Words or TF-IDF)
- ➡️ **Model**: Support Vector Machine (SVM)
- ➡️ **Steps**:
  1. Data Loading & Preprocessing 📊
  2. Feature Extraction 🧬
  3. Model Training 🏋️‍♂️
  4. Evaluation & Prediction 🎯

### 👜 Bag of Words Classifier
*Notebook: `Fake News Classifier using Bag of words.ipynb`*

- ➡️ **Feature Extraction**: Bag of Words (BoW)
- ➡️ **Model**: (Typically Logistic Regression or similar)
- ➡️ **Steps**:
  1. Data Exploration 🔎
  2. Text Vectorization 🧮
  3. Training & Testing 🏁

### 📝 TF-IDF Classifier
*Notebook: `Fake News Classifier using TFIDF.ipynb`*

- ➡️ **Feature Extraction**: TF-IDF Vectorization
- ➡️ **Model**: (Usually Logistic Regression or SVM)
- ➡️ **Steps**:
  1. Data Loading 📥
  2. TF-IDF Transformation ✨
  3. Model Training & Evaluation 🏆

---

## 📊 Dataset

- **train.csv**: Training data (`id`, `title`, `author`, `text`, `label`)
- **test.csv**: Test data
- **submit.csv**: Submission samples

> ⚠️ Place these files inside the `fake-news/` directory!

---

## 🛠️ Installation & Requirements

Install all required libraries in one go:

```bash
pip install numpy pandas scikit-learn notebook
```

- **numpy**: Fast math 🧮
- **pandas**: Data wrangling 🐼
- **scikit-learn**: Machine learning 🤖
- **notebook**: Jupyter interface 📒

---

## 🚀 Usage

1. **Clone the repo**:
    ```bash
    git clone https://github.com/AdishPadalia26/Fake-News-Classifier-Using-NLP.git
    cd Fake-News-Classifier-Using-NLP
    ```
2. **Prepare datasets** in `fake-news/`.
3. **Start Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
4. **Open a notebook** and run the cells! 🏃‍♂️

---

## 🏅 Results

- 📈 Data visualization and summaries
- 🤖 Model accuracy and metrics
- ✅ Prediction outputs

See notebook outputs for details!

---

## 🤝 Contributing

Suggestions, issues, and PRs are welcome! Check [issues](https://github.com/AdishPadalia26/Fake-News-Classifier-Using-NLP/issues) or submit a pull request.

---


## 👤 Author

Developed by **Adish Padalia**  
📧 padaliaadish@gmail.com  
🌐 [GitHub: AdishPadalia26](https://github.com/AdishPadalia26)  
🔗 [LinkedIn: adish-padalia-a3768a230](https://www.linkedin.com/in/adish-padalia-a3768a230/)

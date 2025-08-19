# 📰 Fake News Detection using Machine Learning

## 📌 Project Overview
This project focuses on **detecting fake news** using various Machine Learning models.  
The dataset was downloaded from **Kaggle** and contains labeled news articles (Fake / Real).  

We compare different models and evaluate them on **Accuracy** and **ROC AUC Score** to determine which performs best.

---

## ⚡ Dataset
- Source: [Kaggle Fake News Dataset](https://www.kaggle.com/datasets/aadyasingh55/fake-news-classification)  
- Features: News headlines, text content, labels (fake/real)  
- Target: `label` (True = 1, False = 0)

---

## 🧑‍💻 Models Trained
The following models were trained and evaluated:
- Decision Tree  
- Random Forest  
- XGBoost  
- ExtraTrees  
- LightGBM  

---

## 📊 Results

### 🔹 Accuracy
- **Decision Tree**: 97.54%  
- **Random Forest**: 98.24%  
- **XGBoost**: 98.50%  
- **ExtraTrees**: 97.04%  
- **LightGBM**: 98.45%  

### 🔹 ROC AUC Score
| Model          | ROC AUC Score |
|----------------|---------------|
| Decision Tree  | 97.53%        |
| Random Forest  | 99.55%        |
| XGBoost        | 99.84%        |
| ExtraTrees     | 99.28%        |
| LightGBM       | 99.86%        |

📌 LightGBM achieved the **best performance** with ROC AUC ≈ 0.9986.  

---

## 📷 Visualization
Here is a comparison of ROC AUC scores for all models:

![Model Performance](model-performanv.png)

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
```

### 2️⃣ Install Dependencies
```
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook
```
jupyter notebook FakeNewsDetection.ipynb
```



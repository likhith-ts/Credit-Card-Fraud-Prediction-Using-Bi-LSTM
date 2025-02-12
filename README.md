# Conceive and Empirical Approach for Credit Card Fraud Prediction using Domain Knowledge Learning

![License](https://img.shields.io/github/license/likhith-ts/Credit-Card-Fraud-Prediction-Using-Bi-LSTM)
![Stars](https://img.shields.io/github/stars/likhith-ts/Credit-Card-Fraud-Prediction-Using-Bi-LSTM?style=social)
![Forks](https://img.shields.io/github/forks/likhith-ts/Credit-Card-Fraud-Prediction-Using-Bi-LSTM?style=social)

🚀 **A machine learning project aimed at predicting credit card fraud using Bi-LSTM and ensemble learning techniques.**

---

## 📌 Features
✅ Fraud detection using **Bi-LSTM** for sequential transaction analysis  
✅ **Ensemble learning** (XGBoost, Random Forest, CatBoost) for classification  
✅ **ADASYN oversampling** to handle class imbalance  
✅ Model evaluation with **AUCPR, Precision, Recall, and F1-score**  
✅ Interactive **visualizations for fraud analysis**  

---

## 📂 Dataset
The dataset used for this project is [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.

🔹 **Instances:** 284,807 transactions  
🔹 **Fraud Cases:** 492 fraudulent transactions (highly imbalanced dataset)  
🔹 **Features:** 30 numerical features (including time and amount)

---

## 🏗 Model & Methodology
1️⃣ **Data Preprocessing**: Handling class imbalance with **ADASYN**, feature scaling  
2️⃣ **Feature Engineering**: Extracting insights using **domain knowledge**  
3️⃣ **ML Models Used**: **Bi-LSTM, XGBoost, Random Forest, CatBoost, Gaussian Naïve Bayes, Deep Convolutional Network**  
4️⃣ **Evaluation Metrics**: **AUCPR, Precision, Recall, F1-score, ROC-AUC Curve**  

### 🔬 Key Insights:
- **Bi-LSTM** outperformed traditional classifiers with an **accuracy of 99.8%**.
- **ADASYN oversampling** significantly improved fraud detection recall.
- **Ensemble learning models like XGBoost and Random Forest** were effective but suffered from overfitting without proper tuning.

---

## 🛠 Installation & Usage
### 🔧 Prerequisites
Ensure you have Python 3.8+ and install dependencies:
```bash
pip install -r requirements.txt
```

### 🚀 Running the Project
```bash
python main.py
```

---

## 📊 Results & Performance
| Model            | Accuracy | Precision | Recall | F1-score | AUCPR |
|-----------------|------------|------------|----------|-----------|-----------|
| GaussianNB | 0.95 | 1.00 | 0.95 | 0.97 | 0.89 |
| LightGBM | 1.00 | 0.95 | 0.76 | 0.84 | 0.92 |
| Random Forest | 0.95 | 1.00 | 0.95 | 0.98 | 0.95 |
| CatBoost | 1.00 | 0.70 | 0.83 | 0.76 | 0.93 |
| XGBoost | 0.93 | 1.00 | 0.93 | 0.96 | 0.97 |
| **Deep Convolutional Network** | **0.998** | **0.98** | **0.58** | **0.73** | **0.98** |
| **Bi-LSTM** | **0.998** | **0.93** | **0.70** | **0.81** | **0.99** |

📈 **Key Takeaway**: **Bi-LSTM and Deep Convolutional Network** provided the most balanced results, avoiding overfitting.

---

## 🚀 Future Improvements
- Implementing an **attention mechanism** to enhance Bi-LSTM interpretability.
- Exploring **autoencoder-based oversampling** techniques.
- Developing **real-time fraud detection** using streaming data.

---

## 🤝 Contributing
Pull requests are welcome! Feel free to fork the repo and submit your improvements. 

```bash
git clone https://github.com/likhith-ts/Credit-Card-Fraud-Prediction-Using-Bi-LSTM.git
```

---

## 📬 Contact
For discussions, feel free to reach out via:
- **LinkedIn**: [Likhith Usurupati](https://linkedin.com/in/likhith-usurupati28)
- **Twitter/X**: [@likhith_003](http://x.com/likhith_003)
- **GitHub**: [likhith-ts](https://github.com/likhith-ts)

📢 If you found this useful, consider giving it a ⭐ on GitHub!

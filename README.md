# FEATURE SELECTION IN DETECTING PHISHING ATTACKA DATA DRIVEN APPROACH COMBINING STABILITY, ABLATION AND MACHINE LEARNING MODELS

This project presents a **data-driven approach** to phishing URL detection by combining advanced **feature selection techniques** and **machine learning models**. The goal is to improve phishing detection accuracy and model efficiency using statistical, wrapper, and embedded methods for selecting the most impactful features.

## 📘 Abstract

Phishing is a major cyber threat that involves tricking users into revealing sensitive information. This project leverages machine learning models and multiple feature selection strategies to identify malicious URLs effectively. The dataset consists of over **36,000 URLs** with 80 distinct features.

A combination of 10 feature selection techniques and model evaluation using PyCaret's AutoML led to the selection of **40 optimal features**. The **XGBoost classifier** achieved:
- **Accuracy:** 97.88%
- **F1-Score:** 97.88%
- **ROC AUC:** 0.9990

---

## 📂 Project Structure

```
📁 project-root/
│
├── 📜 MODEL_TRAINING.ipynb      # Jupyter notebook for feature selection & model training
├── 📁 datasets/                 # Phishing dataset (All.csv)
├── 📁 backend/                  # ML backend API (Flask or FastAPI) – optional
└── 📄 README.md                 # Project overview
```

---

## 🧪 Feature Selection Techniques

### Filter-Based:
- Information Gain
- Chi-Square Test
- Fisher Score
- Missing Value Ratio

### Wrapper-Based:
- Forward Selection
- Backward Selection
- Exhaustive Feature Selection
- Recursive Feature Elimination

### Embedded:
- L1 Regularization (LASSO)
- Random Forest Feature Importance

---

## 📊 Model Building & Evaluation

Machine learning models were built using the **PyCaret AutoML** framework. After testing several models, **XGBoost** was selected as the best performing classifier.

### 🔝 Final Model Metrics:
| Metric      | Value     |
|-------------|-----------|
| Accuracy    | 97.88%    |
| Precision   | 97.89%    |
| Recall      | 97.88%    |
| F1 Score    | 97.88%    |
| ROC AUC     | 0.9990    |

---

## 📚 Dataset

- **Source:** Dataset taken from Canadian Institute of Cyber Security
- **Features:** 80 structural, statistical, and entropy-based attributes
- **Classes:** Phishing, Malware, Defacement, Spam, Benign

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/phishing-url-detection.git
cd phishing-url-detection
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open and run the notebook:
```bash
jupyter notebook MODEL_TRAINING.ipynb
```

---

## 🛡️ Key Contributions

- Comprehensive application of 10 feature selection methods
- Use of ablation studies and stability analysis (Kuncheva Index)
- Robust phishing URL classifier using XGBoost
- Real-world applicability with high accuracy and generalizability

---

## 👨‍🎓 Author

- **Name:** Uppara Prakash  
- **Degree:** M.Sc. Computer Science  
- **Institution:** Central University of Tamil Nadu  
- **Guide:** Dr. P. Thiyagarajan

---

## 📬 Contact

For any questions or collaboration:
- **Email:** prakashcutn07@gmail.com
- **LinkedIn:** [www.linkedin.com/in/uppara-prakash-9b5779351]

---

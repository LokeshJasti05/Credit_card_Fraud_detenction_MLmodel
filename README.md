# 📌 Credit Card Fraud Detection

A Machine Learning model to detect fraudulent credit card transactions. This project leverages data preprocessing, feature engineering, and ML algorithms to classify transactions as fraudulent or genuine.

---

## 🚀 Features

- Exploratory Data Analysis (EDA)
- Data Preprocessing (Handling Missing Data, Scaling, etc.)
- Fraud Detection using Machine Learning
- Model Evaluation (Accuracy, Precision, Recall, F1-score)

---

## 🛠️ Tech Stack

**Language**: Python  
**Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn  
**ML Algorithms**: Naïve Bayes, Logistic Regression, Random Forest

---

## 📊 Dataset

**Source**: Kaggle - Credit Card Fraud Dataset  
**Description**: This dataset contains credit card transactions labeled as fraudulent (1) or non-fraudulent (0).  
**Features**:
- `Time`, `Amount` (Transaction details)
- `V1` to `V28` (Anonymized PCA components)
- `Class` (Target variable: 0 = Normal, 1 = Fraud)

---

## 🖥️ Installation & Usage

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/LokeshJasti05/Credit_card_Fraud_detection_MLmodel.git
cd Credit_card_Fraud_detection_MLmodel
```

### 🔹 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 🔹 3. Run the Jupyter Notebook

Open and run all cells in the notebook to train and evaluate the model.

---

## 📌 Note

- If you want to **deploy this model via API (e.g., Flask, FastAPI)** for use in a website or web service, use the **model without the Gradio UI**.
- If you want to **test the model manually**, especially for learning or internal evaluation, use the **model with the Gradio UI** for an interactive experience.

---

## 📈 Results & Evaluation

Model trained using Bayes Decision Theorem achieved **97.64% accuracy**.

**Evaluation Metrics**:

| Metric   | Class 0 | Class 1 |
|----------|---------|---------|
| Precision | 100.00% | 6.00%   |
| Recall    | 98.00%  | 85.00%  |
| F1-score  | 99.00%  | 11.00%  |

---

## 🤝 Contributing

Contributions are welcome!  
Fork this repo and submit a pull request with improvements.

---

## 📜 License

This project is licensed under the MIT License.

---

## 📬 Contact

**📧 Email**: lokesh_jasti@yahoo.com  
**🔗 GitHub**: [LokeshJasti05](https://github.com/LokeshJasti05)

---

🚀 *Happy Coding!*

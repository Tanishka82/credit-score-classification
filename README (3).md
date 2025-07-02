
# 📊 Credit Score Classification using Machine Learning

This project focuses on predicting a customer’s **credit score category** (Good, Standard, Poor) using various financial features. We used **Random Forest**, **XGBoost**, and **SVM** classifiers, applying feature engineering, model tuning, and explainability techniques to build robust and interpretable models.

---

## 🧠 Problem Statement

Financial institutions need reliable models to **predict creditworthiness** of applicants before loan approval. This project aims to classify customers into:

- `Good Credit` (2)
- `Standard Credit` (1)
- `Poor Credit` (0)

based on their financial behavior.

---

## 📁 Project Structure

```
credit-score-classification/
│
├── Credit_Score_Prediction.ipynb    # Main notebook
├── requirements.txt                 # Python dependencies
├── README.md                        # Project overview
├── model/                           # Trained model files 
└── data/                            # Sample data 
```

---

## 📂 Dataset and Model Access
Due to size constraints, the dataset and best model are stored in Google Drive.

➡️ [Download Dataset and Best Model](https://drive.google.com/drive/folders/1l8cabzb9_x-5vN9m68j00wbBczmDa3zm?usp=sharing)

> Please download and upload the files manually before running the notebook.

---

## 📊 Dataset Overview

The dataset includes 100,000 entries and 28 features such as:

- Annual Income
- Monthly In-hand Salary
- Number of Loans & Credit Cards
- EMI per Month
- Credit Mix, Utilization Ratio
- Loan Delay Metrics, etc.

---

## ⚙️ Models Used

| Model          | Accuracy (Before) | Accuracy (After Tuning) |
|----------------|------------------|--------------------------|
| Random Forest  | 81.03%           | 79.65%  ✅ Best                  |
| XGBoost        | 75.03%           | 77.61%            |
| SVM            | 66.86%           | 64.00%                   |

🔍 **Final Model Chosen**: Random Forest (after tuning) due to its better balance of precision, recall, and interpretability.

---

## ✅ Key Features Used

- `credit_activity`
- `income_to_loan_ratio`
- `delay_ratio`
- `loan_burden`
- `Credit_History_Months`
- `Interest_Rate`
- ...and more

---

## 📈 Evaluation Metrics

We used **Accuracy**, **Precision**, **Recall**, and **F1-score** to evaluate performance. Here's a sample classification report:

| Class           | Precision | Recall | F1-Score |
|----------------|-----------|--------|----------|
| Poor Credit (0)  | 0.75     | 0.68   | 0.71     |
| Standard Credit (1) | 0.78  | 0.76   | 0.77     |
| Good Credit (2)  | 0.78     | 0.82   | 0.80     |

---

## 🧪 Model Explainability

We used:

- `Feature Importance (Random Forest)` ✅

---

## 🔍 How to Use

1. Clone this repo:
```bash
git clone https://github.com/Tanishka82/credit-score-classification.git
cd credit-score-classification
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
Open `Credit_Score_Prediction.ipynb` in Jupyter or Google Colab.

---

## 💡 Future Work

- Deploy via Flask API or Streamlit dashboard
- Add deep learning models for comparison
- Include more features like region, industry, etc.

---

## 👨‍💻 Author

Tanishka Patil • [LinkedIn](http://www.linkedin.com/in/tanishkapatil08) • [GitHub](https://github.com/Tanishka82)

---

## ⭐️ Give a Star!

If you found this project helpful, feel free to **⭐️ star** the repo and share!

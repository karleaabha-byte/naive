
# 🧠 Naive Bayes Classifier Web App

An interactive Machine Learning web application built using **Streamlit** and **Scikit-Learn**.

This app allows users to upload any CSV dataset, select a target column, train a **Gaussian Naive Bayes classifier**, and evaluate model performance instantly.

---

## 🚀 Features

* 📂 Upload any CSV dataset
* 🎯 Select target column dynamically
* 📊 Adjustable train-test split
* 🧠 Gaussian Naive Bayes model
* ✅ Accuracy score
* 🔎 Confusion matrix visualization
* 📈 Scatter plot (if dataset has exactly 2 features)

---

## 📊 How It Works

1. Upload a dataset (CSV format)
2. Select the target column
3. Adjust test size percentage
4. Model trains automatically
5. View performance metrics and visualizations

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/naive.git
cd naive
```

---

### 2️⃣ (Optional) Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the App

```bash
streamlit run app2.py
```

---

## 📦 Requirements

Your `requirements.txt` should contain:

```
streamlit
pandas
numpy
scikit-learn
matplotlib
```

---

## 🧠 Model Used

**Gaussian Naive Bayes (Scikit-Learn)**

Best suited for:

* Multi-class classification
* Continuous numerical features
* Educational ML demonstrations

---

## 📌 Example Datasets

* Iris Dataset
* Credit Dataset
* Any classification dataset (CSV format)

---

## 🔮 Future Improvements

* Precision, Recall, F1-score
* ROC Curve
* Model comparison (Logistic Regression, SVM)
* Cross-validation
* Deployment optimization

---

## 👨‍💻 Author

Built as a Machine Learning practice and portfolio project.

---



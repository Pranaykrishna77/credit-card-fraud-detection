
# 💳 credit-card-fraud-detection

A Machine Learning project to detect fraudulent credit card transactions using Random Forest, Logistic Regression, and Support Vector Machine (SVM) models. The model is trained and evaluated on a real-world credit card transaction dataset using Python and Jupyter (Google Colab).

---

## 📁 Project Structure

```

credit-card-fraud-detection/
├── Credit\_card\_fraud\_detection.ipynb     # Main notebook
├── requirements.txt                      # List of required packages
├── .gitignore                            # Git ignored files
└── README.md                             # Project documentation

````

---

## 🧠 Models Implemented

- **Random Forest Classifier**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

Each model is evaluated using:
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score

---

## 📊 Dataset

This project uses the dataset from Kaggle:

🔗 [Credit Card Fraud Detection Dataset – Dhanush Narayanan R](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud)

The dataset contains anonymized credit card transaction data labeled as fraudulent or legitimate.

---

## 🚀 How to Run

### Clone the Repository
```bash
git clone https://github.com/Pranaykrishna77/credit-card-fraud-detection
cd credit-card-fraud-detection
````

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch the Notebook

* Open `Credit_card_fraud_detection.ipynb` in Jupyter or [Google Colab](https://colab.research.google.com/).
* Follow the notebook cells to run preprocessing, training, and model evaluation.

---

## 📦 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

This project primarily uses:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

---

## 🧹 Data Preprocessing Includes

* Handling missing values
* Data normalization and scaling
* Feature importance and selection
* Class imbalance handling (e.g., via undersampling or class weights)

---

## ✅ Results

* Evaluated and compared performance of all models
* Insights from confusion matrix and feature importance
* Random Forest yielded highest precision and recall in this project

---

## 📌 Conclusion

This project showcases the effectiveness of ensemble and linear classifiers in identifying fraudulent transactions from imbalanced datasets. It serves as a base template for financial fraud detection problems.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss improvements or enhancements.

---

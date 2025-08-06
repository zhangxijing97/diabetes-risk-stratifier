# diabetes-risk-stratifier

This project demonstrates and compares multiple machine learning models to classify diabetes risk levels based on health indicators. The dataset used is the **Diabetes Health Indicators Dataset** from Kaggle.

## 🔍 Objective

To identify individuals at higher risk of diabetes using classification models — a concept aligned with Abacus Health Solutions' focus on proactive risk stratification to reduce healthcare costs and improve patient outcomes.

## 📊 Dataset

- **Source**: [Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
- **Features**: Various health and lifestyle metrics (BMI, smoking, stroke history, physical activity, etc.)
- **Target**: Diabetes status (0 = No diabetes, 1 = Pre-diabetes, 2 = Diabetes)

## 🧠 Models Compared

| Model                | Accuracy |
|---------------------|----------|
| LightGBM            | 0.8493   |
| Gradient Boosting   | 0.8491   |
| Random Forest       | 0.8433   |
| Logistic Regression | 0.6458   |

✅ **Best Model:** LightGBM

## ⚙️ Environment

- Python 3.11
- Jupyter Notebook
- scikit-learn
- lightgbm
- pandas, numpy, matplotlib

## 📁 Structure

```
📦diabetes-risk-stratifier/
 ┣ 📜diabetes_model.ipynb         # Main notebook with preprocessing, training, evaluation
 ┣ 📜requirements.txt             # Dependencies
 ┗ 📜README.md                    # This file
```

## 🚀 How to Run

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Launch Jupyter Notebook and open `diabetes_model.ipynb`

## 📌 Notes

- All models are trained and tested using consistent preprocessing
- StandardScaler is applied for Logistic Regression
- Accuracy and classification report are printed for comparison

## 📄 License

MIT
# 💓 Heart Disease Prediction - ML Project

This project uses machine learning to predict whether a person is likely to have heart disease based on various medical attributes. The dataset is publicly available and contains features such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

---

## 📁 Project Structure
📦 heart-disease-prediction/
- ├── Heart-disease-prediction-ML.ipynb             # Jupyter Notebook with full EDA, model building & evaluation
- ├── heart-disease.csv                             # Dataset used for training/testing
- ├── README.md                                     # Project overview (this file)

---

## 🚀 Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression, KNN, Random Forest)
- Hyperparameter Tuning with RandomizedSearchCV

---

## 📊 Dataset Overview

The dataset contains the following features:

- **age**: Age of the patient
- **sex**: 1 = male; 0 = female
- **cp**: Chest pain type (0–3)
- **trestbps**: Resting blood pressure
- **chol**: Serum cholesterol (mg/dl)
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg**: Resting electrocardiographic results (0–2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise-induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise
- **slope, ca, thal**: Additional ECG/scan results
- **target**: 1 = heart disease, 0 = no heart disease

---

## 🔍 Steps Followed

1. Data Cleaning & EDA
2. Data Visualization
3. Model Training & Testing
4. Model Comparison
5. Hyperparameter Tuning
6. Final Accuracy Scores with Annotations

---

## 🧠 Best Performing Model

- **Logistic Regression** performed best with ~88% accuracy after hyperparameter tuning.
- Also tried **K-Nearest Neighbors** and **Random Forest** for comparison.

---

## 📈 Example Visualizations

- Heart disease frequency by gender
- Correlation heatmap
- Model accuracy comparison (bar plot with annotations)

---

## 🏁 How to Run

1. Clone the repository
2. Open `Heart-disease-prediction-ML.ipynb` in Jupyter Notebook
3. Run all cells to see outputs and visualizations

---

## 📌 Future Improvements

- Add web UI (e.g., Flask or Streamlit) for predictions
- Try more advanced models like XGBoost or Neural Networks
- Add SHAP/LIME for model interpretability

---

## 🤝 Contributing

Pull requests are welcome! If you find any issues or have suggestions, feel free to open one.


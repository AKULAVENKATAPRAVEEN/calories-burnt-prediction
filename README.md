# 🏃 Calories Burned Prediction using Machine Learning

This project predicts the number of **calories burned** during exercise based on physiological attributes using **Random Forest Regression**.

---

## 📌 Dataset

Combined from two CSV files:
- `exercise.csv` – Contains user data like Gender, Age, Height, Weight, Duration, Heart Rate, and Body Temperature.
- `calories.csv` – Contains corresponding calories burned by each user.

Dataset source: Kaggle  
Notebook Reference: [Muskan Jha – Kaggle Notebook](https://www.kaggle.com/code/muskanjha/calories-burnt-prediction)

---

## 💻 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## ✅ Features Used

- Gender (encoded)
- Age
- Height (in cm)
- Weight (in kg)
- Duration (in minutes)
- Heart Rate (bpm)
- Body Temperature (°C)

---

## 🧠 Model Used

- RandomForestRegressor from Scikit-learn

---

## 🧪 Evaluation Metrics

- Mean Absolute Error (MAE)
- R² Score

---

## 📈 Sample Prediction

```python
sample_input = pd.DataFrame({
    'Gender': [1],
    'Age': [25],
    'Height': [165],
    'Weight': [60],
    'Duration': [30],
    'Heart_Rate': [120],
    'Body_Temp': [37.5]
})

model.predict(sample_input)

# ❤️ Heart Disease Prediction using Logistic Regression

This project is a machine learning-based solution that predicts whether a person has heart disease based on various medical parameters. It uses **Logistic Regression**, a supervised classification algorithm, to train a predictive model using the popular **Heart Disease UCI dataset**.

---

## 📂 Project Structure

The project covers the full pipeline from data loading to prediction:

1. Importing Dependencies  
2. Data Collection and Preprocessing  
3. Splitting Features and Target  
4. Train-Test Split  
5. Model Training  
6. Model Evaluation  
7. Building a Predictive System  

---

## 🧠 Algorithm Used

- **Logistic Regression** (suitable for binary classification)

---

## 📊 Dataset

- Source: [`heart.csv`](https://www.kaggle.com/datasets/mragpavank/heart-diseaseuci?resource=download)  
- The dataset contains medical records with the following features:
  - `age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`
- **Target column**: `target`  
  - `1`: Person has heart disease  
  - `0`: Person does not have heart disease

---

## 📈 Model Accuracy

- ✅ **Training Accuracy**: `85.48%`  
- ✅ **Testing Accuracy**: `81.96%`

---

## 🔮 Sample Prediction

### ▶️ Sample Input:
```python
input_data = (62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2)
```
#### Output: The Person has Heart Disease

## 🛠️ Tools Used

- python, NumPy, Pandas, Scikit-learn

# 🚢 Titanic Survival Classification

This project is part of the **Data Science Internship at Arch Technologies**. The goal is to build a machine learning model that predicts whether a passenger on the Titanic survived or not based on features like age, gender, ticket class, fare, etc.

---

## 📁 Dataset

The dataset used is from the [Kaggle Titanic Challenge](https://www.kaggle.com/competitions/titanic/data) and includes:
- `train.csv`: Training data
- `test.csv`: Test data
- `titanic_submission.csv`: Final predictions file

---

## 📊 Technologies Used

- Python 🐍
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## ✅ Project Steps

1. **Data Cleaning**
   - Filled missing values (`Age`, `Embarked`, `Fare`)
   - Dropped irrelevant columns like `Cabin`
   
2. **Feature Engineering**
   - Converted categorical features (`Sex`, `Embarked`) to numeric
   - Selected key features for training

3. **Model Training**
   - Used Logistic Regression and Random Forest Classifier
   - Evaluated models using accuracy, confusion matrix, and classification report

4. **Visualization**
   - Created plots to understand survival trends by gender, class, and age

5. **Prediction**
   - Made survival predictions on test dataset using the trained Random Forest model

---

## 📈 Model Performance

**Random Forest Classifier:**
- Accuracy: ~81.6%
- F1-Score (Survived): 0.77

---

## 📂 Files in this Repo

| File                     | Description                                |
|--------------------------|--------------------------------------------|
| `titanic_model.ipynb`    | Main Jupyter notebook with code & plots    |
| `titanic_submission.csv` | Final prediction for submission            |
| `train.csv`              | Training dataset from Kaggle               |
| `test.csv`               | Test dataset from Kaggle                   |

---

## ✍️ Author

**Ayesha Nadeem**  
Data Science Intern – July 2025  
Arch Technologies

---

## 📧 Contact

For technical issues or feedback:  
📩 ayeshanadeem2408@gmail.com


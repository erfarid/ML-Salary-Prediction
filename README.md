# 💼 Salary Prediction Using Machine Learning

This project aims to predict employee salary using machine learning techniques based on features such as experience level, employment type, job title, and company details.

---

## 📌 Project Overview

This project follows these steps:

1. **Dataset Selection**  
   The dataset was obtained from Kaggle: *"Salary Dataset - 2024"*.

2. **Data Exploration**  
   Performed data inspection, statistical summary, missing value analysis, and visualization (salary distribution, salary by experience level, top job titles).

3. **Feature Engineering**  
   Encoded categorical variables using `OneHotEncoder`.

4. **Model Training**  
   Trained a regression model (`RandomForestRegressor`) to predict salary.

5. **Model Evaluation**  
   Evaluated using **R² Score** and **Mean Squared Error (MSE)**.

---

## 🔍 Technologies Used

| Component        | Tool/Library      |
|------------------|------------------|
| Language         | Python           |
| Notebook         | Jupyter Notebook |
| Machine Learning | Scikit-learn     |
| Data Handling    | Pandas           |
| Visualization    | Matplotlib, Seaborn |

---

## 📁 How to Run the Project

```bash
# Clone repository
git clone https://github.com/yourusername/ML-Salary-Prediction.git

# Navigate to folder
cd ML-Salary-Prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook

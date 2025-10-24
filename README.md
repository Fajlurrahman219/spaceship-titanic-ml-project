
# 🚀 Spaceship Titanic – Machine Learning Classification Project

### 🧠 Overview
This project is based on the **Kaggle Spaceship Titanic Competition**, a futuristic twist on the classic Titanic dataset.  
The goal is to **predict whether a passenger was transported to an alternate dimension** after the spaceship Titanic encountered a spacetime anomaly.

It’s the year 2912 — and your mission as a Data Scientist is to help solve this interstellar mystery using **data-driven insights**.

---

### 🎯 Objective
The main objective of this project is to build a **binary classification model** that predicts the “Transported” status (Yes/No) of each passenger.

---

### 📚 Project Workflow
1. **Data Understanding** – Loading and exploring the dataset to understand the structure and missing values.  
2. **Exploratory Data Analysis (EDA)** – Visualizing passenger demographics, spending patterns, and transport outcomes.  
3. **Feature Engineering** – Creating new meaningful features and encoding categorical data.  
4. **Data Preprocessing** – Handling missing values, scaling numerical columns, and preparing data for modeling.  
5. **Model Building** – Training and evaluating different machine learning models (Logistic Regression, Random Forest, XGBoost, etc.).  
6. **Hyperparameter Tuning** – Optimizing model performance using GridSearchCV.  
7. **Prediction** – Making final predictions on the test dataset using the best-performing model.

---

### 🧩 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - xgboost

---

### 📊 Results & Insights
- The final model achieved high accuracy and provided key insights into the factors influencing passenger transportation.  
- Features like **CryoSleep**, **Cabin Location**, and **Spending on Amenities** had strong correlations with the outcome.

---

### 🏆 Model Performance

| Model | Accuracy | F1 Score | Comments |
|-------|-----------|-----------|-----------|
| Logistic Regression | 0.79 | 0.78 | Baseline model |
| Random Forest | 0.83 | 0.82 | Good generalization |
| XGBoost | **0.85** | **0.84** | Best performing model |

---

### 💡 Key Learnings
- Improved accuracy through feature engineering and parameter tuning.  
- Learned the importance of handling missing values carefully.  
- Understood the impact of categorical encoding and feature scaling on model performance.  
- Practiced model comparison and hyperparameter optimization techniques.  

---

### 📁 Dataset
The dataset is sourced from the official Kaggle competition:  
🔗 [Spaceship Titanic on Kaggle](https://www.kaggle.com/competitions/spaceship-titanic)

It contains columns like:  
- `PassengerId`, `HomePlanet`, `CryoSleep`, `Cabin`, `Destination`, `Age`, `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck`, `Transported`.

---

### ⚙️ How to Run Locally
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/spaceship-titanic.git
   cd spaceship-titanic
   ```
2. Install required libraries  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook  
   ```bash
   jupyter notebook Spaceship_Titanic.ipynb
   ```
4. Run all cells to reproduce the results.

---

### 🧑‍💻 Author
**Fajlur Rahman**  
- Data Scientist | Machine Learning Enthusiast  
- 🔗 [LinkedIn](https://www.linkedin.com/in/fajlurrahman219)  
- 📧 fajlurrahman219@gmail.com

---

### ⭐ Contribute
Contributions, feedback, and suggestions are welcome! Feel free to fork this repo and raise a pull request.

# ⚽ Project: Player Rating Analysis

Welcome to our 4th semester machine learning project — **Player Rating Analysis**.  
This project aims to predict and analyze player ratings using statistical features and machine learning models, with custom logic to reflect the real impact of player positions.

## 📊 Objective

To build a system that can analyze and predict player performance ratings based on various match and player-related statistics like:
- Goals
- Assists
- Position
- Nationality
- Club

The ratings are influenced by **custom position-based weight logic** that adds realism and fairness to the rating mechanism.

---

## 🧠 Key Features

- ⚙️ **Data Preprocessing**: 
  - Categorical encoding using `OneHotEncoder`
  - Feature scaling with `StandardScaler`
  - Combined using `ColumnTransformer`

- 🔁 **Model Training**:
  - Support Vector Regressor (SVR)
  - Random Forest Regressor
  - XGBoost Regressor

- 🧮 **Custom Logic**:
  - Dynamic weight assignment depending on player roles
  - For example:
    - A defender scoring a goal has **higher impact** than a striker
    - Assists by midfielders are **weighed more** than those by forwards

- 📈 **Model Evaluation**:
  - Compare predicted vs. actual ratings
  - Measure performance using metrics like MAE, RMSE, and R² Score

---

## 🧰 Tech Stack & Tools

- **Language**: Python 🐍
- **Libraries**:
  - `pandas`, `numpy` – Data processing
  - `scikit-learn` – Preprocessing, SVR, evaluation
  - `xgboost` – XGBoost Regressor
  - `matplotlib`, `seaborn` – Visualization



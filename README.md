# 🏡 Predict Real Estate Prices

## 📌 Overview
This project predicts housing prices using the **Boston Housing Dataset**.  
We apply data cleaning, exploratory data analysis (EDA), and modeling using **XGBoost Regressor**.

---

## 📂 Dataset
- **Source**: [Boston Housing Dataset on Kaggle](https://www.kaggle.com/datasets/altavish/boston-housing-dataset)  
- **Rows**: 506  
- **Columns**: 13 features + 1 target (`Price`)

Key Features:
- `CRIM`: Crime rate per capita  
- `RM`: Average number of rooms per dwelling  
- `LSTAT`: % lower status population  
- `PTRATIO`: Pupil-teacher ratio  
- `Price`: Median value of homes (Target)

---

## 🛠️ Workflow
1. **Data Preprocessing**
   - Handle missing values
   - Drop duplicates
   - Rename target column (`MEDV` → `Price`)

2. **Exploratory Data Analysis**
   - Summary statistics
   - Correlation heatmap
   - Distribution plots

3. **Modeling**
   - Split dataset: 80% train, 20% test
   - Model: `XGBRegressor`
   - Evaluation: R² Score & MSE

---

## 📊 Results
- **R² Score**: `0.874`
- **MSE**: `14.067`

✅ The model explains ~87% variance in housing prices with relatively low error.

---

## 🚀 Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/abdosaied22/Predict-real-estate-prices.git
cd Predict-real-estate-prices
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the script
```bash
python main.py
```

Or open the Jupyter Notebook to explore step by step:
```bash
jupyter notebook
```

---

## 📌 Future Improvements
- Hyperparameter tuning for XGBoost  
- Try other models (Random Forest, CatBoost, Linear Regression)  
- Feature engineering & scaling  
- Cross-validation for robust performance  

---

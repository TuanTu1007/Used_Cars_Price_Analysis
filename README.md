# Used Car Price Prediction

**Result:** Built multiple regression models to predict used car prices with up to **95% R² score**.  

## 🧰 Technologies Used
- Python  
- Scikit-Learn  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Power BI  

## 📂 Project Structure

```
Used_Cars_Price_Analysis/
├── Dataset_Car/
│ ├── test-data.csv
│ ├── train-data.csv
│ └── train-data-clean.csv
├── Report/
│ └── Report_Final_IE224.docx
├── Source/
│ ├── describe_data.ipynb
│ ├── EDA_Modeling_data.ipynb
│ └── preprocessing_data.ipynb
└── README.md
```

## 🔍 Data
- `train-data.csv`: Original training data.  
- `train-data-clean.csv`: Cleaned and preprocessed version used for modeling.  
- `test-data.csv`: Held-out data for final evaluation.

## 🧪 Models Built
- **Linear Regression**: Baseline model to capture linear relationships.  
- **Polynomial Regression**: Captured non-linear patterns by expanding feature space.  
- **Random Forest Regression**: Ensemble model for robust, non-parametric prediction.

## 📈 Evaluation
- Compared models using:
  - **R² Score** (up to 95% for best model)  
  - **Root Mean Squared Error (RMSE)**  
  - **Mean Absolute Error (MAE)**  
- Visualized residuals, prediction vs. actual plots, and feature importance to interpret model behavior.



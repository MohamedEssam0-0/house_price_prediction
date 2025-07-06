# house_price_prediction
# 🏡 Ames Housing Price Prediction

This project uses the Ames Housing dataset to predict house prices using machine learning. The dataset contains detailed information about residential homes in Ames, Iowa.

## 📌 Project Goals

- Predict house prices based on important property features
- Apply linear regression to estimate prices
- Evaluate model performance using RMSE and R² Score
- Visualize predictions and feature importance

## 🧠 Skills Used

- Data preprocessing and cleaning
- Feature selection and encoding
- Linear regression modeling (with `scikit-learn`)
- Model evaluation (RMSE, R²)
- Data visualization with Matplotlib

## 📊 Dataset

- **Source**: [Ames Housing dataset](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- **Records**: ~2930 homes
- **Features**: 80+ attributes like living area, garage size, year built, and more

## ⚙️ How It Works

1. Load and explore the dataset
2. Clean missing values and drop high-missing columns
3. Select key features influencing price
4. Encode categorical features (like zoning and air conditioning)
5. Train/test split
6. Apply Linear Regression
7. Visualize predictions and feature importance

## 📈 Results

- **RMSE**: ~39,610
- **R² Score**: ~0.80
- Top influential features: `Gr Liv Area`, `Overall Qual`, `Garage Cars`, `MS Zoning`

## 📷 Visuals

![Predicted vs Actual](./images/actual_vs_predicted.png)  
*Actual vs. Predicted House Prices*

![Feature Importance](./images/feature_importance.png)  
*Feature Impact in Linear Regression*

## 💡 Future Improvements

- Try XGBoost or Random Forest
- Hyperparameter tuning
- Cross-validation

## 🧑‍💻 Author

- Mohamed Shafey  
- Master’s project in Machine Learning & AI  
- 📍 Based in Berlin  

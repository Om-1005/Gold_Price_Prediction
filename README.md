# Gold Price Prediction using Random Forest

## Overview
This project aims to predict **gold prices** using historical data and machine learning techniques. We utilize the **Random Forest Regressor** to build a predictive model based on key financial indicators.

## Dataset
- The dataset contains **gold price data** with various economic indicators.
- Source: Kaggle.
- Preprocessing steps include handling missing values, converting dates, and feature engineering.

## Technologies Used
- **Python** (pandas, NumPy, scikit-learn, Matplotlib, Seaborn)
- **Machine Learning** (Random Forest Regressor)
- **Google Colab**

## Workflow
1. **Data Preprocessing**
   - Load dataset
   - Handle missing values
   - Convert date columns and extract useful features
2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis
   - Feature selection
3. **Model Training**
   - Train a **Random Forest Regressor**
   - Tune hyperparameters using GridSearchCV
4. **Evaluation**
   - Measure performance using RMSE, MAE, and R² score
5. **Predictions & Visualization**
   - Plot actual vs predicted values
   - Feature importance analysis

## Results
- The Random Forest model achieves **high accuracy** in predicting gold prices.
- Feature importance analysis shows that **economic indicators like USD index, interest rates, and oil prices** impact predictions.

## How to Run the Project on Google Colab
1. Open Google Colab: [Google Colab](https://colab.research.google.com/)
2. Upload the dataset to Colab or mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

## Future Improvements

- Use Deep Learning (LSTMs) for time-series forecasting.

- Integrate real-time data for live price prediction.

- Implement web-based visualization using Flask/Streamlit.



## Contributors  
- **Your Name**  
  - 📧 Email: [omtamkhane97@gmail.com](mailto:your.email@example.com)  
  - 🔗 LinkedIn: [Om Tamkhane](https://www.linkedin.com/in/om-tamkhane-18b8622b5/)  

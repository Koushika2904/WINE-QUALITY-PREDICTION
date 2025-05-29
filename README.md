# Wine Quality Prediction Model

This project is a machine learning-based system developed to predict the quality of red and white wines based on physicochemical attributes. The analysis is performed using the `winequality-red.csv` and `winequality-white.csv` datasets. The implementation is done in a Jupyter Notebook or Google Collab and includes data preprocessing, exploratory data analysis, model building, and evaluation.

## 📂 Project Structure

- `Wine_Quality_Prediction_final.ipynb` – Main Jupyter Notebook containing the complete code.
- `winequality-red.csv` – Dataset containing red wine samples with physicochemical features and quality ratings.
- `winequality-white.csv` – Dataset containing white wine samples with physicochemical features and quality ratings.

## 📊 Datasets

Both datasets contain the following features:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target Variable)

Source: UCI Machine Learning Repository

## 🔧 Technologies Used

- Python
- Jupyter Notebook or Google Collab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## 🔍 Workflow Overview

1. **Data Loading**  
   Load red and white wine datasets using pandas.

2. **Data Preprocessing**  
   - Merge datasets.
   - Handle missing values if any.
   - Label encoding and feature scaling.

3. **Exploratory Data Analysis (EDA)**  
   - Visualize distributions and correlations.
   - Check feature importance.

4. **Model Building**  
   - Models used: Random Forest Regressor, XGBoost Regressor.
   - Train/test split.

5. **Model Evaluation**  
   - Metrics: Mean Squared Error (MSE), R² Score.
   - Comparison of models on performance metrics.

## 📈 Results

The best-performing model achieved:

- High R² score (indicating good predictive performance).
- Low MSE on the test data.

These results indicate the model's effectiveness in predicting wine quality using physicochemical inputs.

## 📌 Conclusion

This project successfully demonstrates the application of machine learning in the food and beverage industry, particularly in wine quality control. Feature importance analysis also helps understand which chemical properties most influence wine quality.

## 📎 References

- [UCI Machine Learning Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- Scikit-learn Documentation
- XGBoost Documentation

---

## 🚀 How to Run

1. Clone the repository or download the files.
2. Open the `Wine_Quality_Prediction_final.ipynb` file in Jupyter Notebook or any compatible environment.
3. Run the notebook step-by-step to see the complete analysis and model predictions.


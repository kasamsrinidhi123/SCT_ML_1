# SCT_ML_1
# House Price Prediction using Linear Regression

## Project Description
This project predicts house prices based on selected features such as living area size, number of bedrooms, and number of bathrooms. Using a **Linear Regression model**, it analyzes historical housing data and provides predictions for new houses. The model is evaluated using R² Score and RMSE to measure its performance.

---

## Project Highlights
- Built a **predictive model** using Linear Regression.
- Selected important features from the dataset for training.
- Visualized **Actual vs Predicted** prices for performance analysis.
- Evaluated model accuracy using **R² Score** and **RMSE**.
- Added functionality to predict prices for **new house inputs**.

---

## Key Steps
1. **Load and Prepare Data**
   - Import dataset from `train.csv`.
   - Select relevant features and handle missing values.
2. **Split Data**
   - Train-test split to validate performance.
3. **Model Training**
   - Fit a Linear Regression model using `scikit-learn`.
4. **Prediction & Evaluation**
   - Evaluate using R² Score & RMSE.
   - Visualize predictions with a scatter plot.
5. **Future Prediction**
   - Predict price for a new house with given parameters.

---

## Technologies Used
- **Python 3.x**
- **Pandas** – Data loading & preprocessing.
- **NumPy** – Numerical computations.
- **Scikit-learn** – Linear Regression & Model Evaluation.
- **Matplotlib** – Visualization of results.

---

## How to Run
1. Install required libraries:
```bash
pip install pandas scikit-learn matplotlib numpy

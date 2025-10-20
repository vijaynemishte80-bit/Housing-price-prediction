# Housing Price Prediction Using Linear Regression & Random Forest

## Project Overview
This project predicts housing prices using the *California Housing dataset. It demonstrates how **Linear Regression* and *Random Forest Regression* models can be applied to real-world data for price prediction. The goal is to compare the performance of both models and understand which model predicts housing prices more accurately.

---

## Dataset
- *Source:* California Housing dataset from sklearn.datasets
- *Features:*
  - MedInc : Median income of households
  - HouseAge : Age of the house
  - AveRooms : Average number of rooms per house
  - AveBedrms : Average number of bedrooms
  - Population : Population in the block
  - AveOccup : Average occupancy per house
  - Latitude : Latitude coordinate
  - Longitude : Longitude coordinate
- *Target:* MedHouseValue (Median house value)

---

## Data Preprocessing
1. *Feature Selection:* Only the relevant features are selected for prediction.
2. *Train-Test Split:* Dataset is split into *80% training* and *20% testing* sets.
3. *Scaling:*
   - Features are scaled using *StandardScaler* for better model performance.
   - Target is scaled to *USD* (median house value × 100,000).

---

## Models
1. *Linear Regression* – Simple model to understand the relationship between features and target.
2. *Random Forest Regression* – Ensemble method to capture non-linear relationships and improve prediction accuracy.

---

## Evaluation Metrics
- *Mean Squared Error (MSE)*
- *Root Mean Squared Error (RMSE)*
- *R² Score* – Measures model accuracy

---

## Results
- Comparison of the first 10 predictions for both models vs actual house prices.
- *Plots included:*
  - Actual vs Predicted prices
  - Residual plots

> Random Forest Regression generally provides *higher accuracy* compared to Linear Regression.

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/YourUsername/Housing-Price-Prediction.git

# RANDOM-FOREST-REGRESSOR
A Machine Learning project that predicts startup profit using a Random Forest Regressor. The model learns from R&amp;D, administration, marketing spend, and state data to make accurate profit predictions. Built with Scikit-learn, evaluated using R² score, and saved with pickle for easy reuse and future predictions.
# Startup Profit Prediction using Random Forest Regression

This project uses a **Random Forest Regressor** to predict the profit of a startup based on important business factors like R&D Spend, Administration, Marketing Spend, and State.

It demonstrates a complete Machine Learning pipeline including preprocessing, model training, evaluation, and model saving for future use.

---

## Dataset

The dataset used is `50_Startups.csv` and contains:

- **R&D Spend**
- **Administration**
- **Marketing Spend**
- **State** (Categorical feature)
- **Profit** (Target variable)

---

##  Technologies Used

- Python
- Pandas
- Scikit-learn (RandomForestRegressor)
- Pickle (for model persistence)

---

## Project Workflow

1. Load the dataset using Pandas
2. Encode the categorical feature (**State**)
3. Split the data into training and testing sets
4. Train a **Random Forest Regression** model
5. Evaluate the model using **R² score**
6. Save the trained model using pickle
7. Use the saved model to predict profit for new inputs

---

## Model Details

- Algorithm: **Random Forest Regressor**
- Test Size: 30%
- Evaluation Metric: R² Score
- Ensemble of multiple decision trees for better accuracy

---

## Model Saving

The trained model is saved as: finalized_model_MLR.sav


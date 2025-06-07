# F1_Canada2025_Prediction


This project focuses on data cleaning, exploration, and prediction for the Formula 1 Canadian Grand Prix using historic F1 datasets. The core objective is to predict the winning constructor (team) for future Canadian Grand Prix races using machine learning techniques.

**Objective**

To predict whether a constructor (team) would win the Canadian Grand Prix based on performance features such as:
- Grid position

- Fastest lap

- Points scored

- Status of race completion

- Rank

- Constructor ID

**Feature Engineering**

The following preprocessing steps were used:

Label encoding for categorical features like constructorRef, fastestLap, and rank.

Derived a target variable is_winner from position order.

Created a balanced feature matrix (X) and target vector (y).


**Machine Learning Model**


Model Used: Random Forest Classifier

Train-Test Split: 80/20 split using stratified sampling

The model was trained on historical data and evaluated for prediction accuracy.

Used a mock dataset to predict outcomes for constructors in a hypothetical 2025 Canadian Grand Prix.

**Predictions**

The model predicts the likelihood of each constructor winning the race based on engineered features. For instance:

Red Bull starting at grid 1 may have a high probability of winning.

Lower grid positions generally have lower chances unless compensated by better lap and rank data.

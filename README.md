# Prediction of Inorganic ABX3 Perovskite Material Properties Using ML 
  
## Project Overview:
  This repository presents the code and data for a comprehensive machine learning (ML) study focused on the prediction a of key properties of ABX3 inorganic perovskite materials using regression models.The dataset, originally sourced from the Open Quantum Materials Database (OQMD), contains 16,323 samples of perovskite structures and is designed for use in ML models to predict deterministic target properties. These target properties include:

* Formation energy
* Band gap energy

The dataset has been preprocessed to include 61 input features that describe the physicochemical, stability/geometrical, and Density Functional Theory (DFT) properties of the material, making it suitable for benchmark analysis in ML-driven materials discovery.

## Dataset:
* Source: Open Quantum Materials Database (OQMD)
* Size: 16,323 samples
* Features: 61 input features, including descriptors related to elemental sites in the ABX3 polyhedral and DFT-calculated properties.
* Target Variables: Formation energy (eV/atom) and Band gap energy (eV)


## Machine Learning Models:
Three different ML models were employed to predict the target properties:

1. Lasso Regression
2. Random Forest
3. XGBoost

## Performance:
The ML models were optimized using extensive hyperparameter tuning via Optuna and validated through 5-fold cross-validation. The best-performing models achieved the following results:

* Formation energy prediction: 0.24 eV/atom Mean Absolute Error (MAE)
  
These results affirm the robustness of the dataset for predicting material properties.

## Key Features:
* Data Preprocessing: Handling of missing data, outlier removal, and feature scaling.
* Exploratory Data Analysis (EDA): Visualizations and statistical summaries to understand the dataset.
* Feature Engineering: Automatic feature selection and transformation techniques.
* Hyperparameter Optimization: Optuna is used to fine-tune the models to improve accuracy and reduce errors.
* Cross-validation: Ensures model generalization with 5-fold validation.

## Installation and Dependencies:
To replicate the results in this repository, you will need the following libraries:

* numpy
* pandas
* scikit-learn
* xgboost
* optuna
* matplotlib
* seaborn

Install the dependencies using pip:
   pip install -r requirements.txt

## How to Use:

1. Clone the repository:
     git clone https://github.com/Pracheeyadav2022/ML-Based-Prediction-and-Classification-of-ABX3-Perovskite-Properties.git
2. Load the preprocessed dataset (oqmd_data.csv) which includes the 61 input features.
3. Choose the model you want to run (Lasso, Random Forest, XGBoost) in the provided script.
4. Run the code to train and evaluate the models.
5. Use Optuna for hyperparameter tuning if desired.

## Results and Future Work:
The models have demonstrated excellent predictive performance, particularly for formation energy and band gap. Future improvements may include:

* Expanding the dataset to include more perovskite structures.
* Applying deep learning techniques for better feature extraction and prediction.
* Further refining the feature engineering pipeline for improved performance.

       


  

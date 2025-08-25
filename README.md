# Random-Forest-Obesity-Tuner
obesity prediction using concept of linear regression and decsion tress with the hyper parameter tuning of random forests

## Overview
This notebook trains a **Random Forest Regressor** to predict population-level obesity rates and **automatically tunes** its hyper-parameters (`n_estimators`, `max_depth`, `min_samples_leaf`) with `GridSearchCV`.  
It uses a small toy dataset (10 rows) that mimics CDC behaviour trends—you can swap in any CSV once your data are in a pandas DataFrame.

**What you get**
- End-to-end code in ONE cell: data setup ➜ train/test split ➜ grid search ➜ best-model evaluation ➜ feature-importance plot.
- Prints best parameter combo and cross-validated R², then reports real test R²/RMSE.
- Horizontal bar chart ranks which lifestyle factors drive obesity in the tuned model.

## Quick Start
1. Clone or open in Colab.
2. Install deps if needed:
pip install pandas numpy scikit-learn matplotlib

text
3. Run the single code cell.  
Replace the `data` dictionary with your own DataFrame for real analysis.

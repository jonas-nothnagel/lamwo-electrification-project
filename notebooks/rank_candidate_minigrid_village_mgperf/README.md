# Rank Minigrid Villages using minigrid performance (mgperf)

This folder contains machine learning scripts to rank villages for minigrid deployment based on a score `mgperf` that is a prediction of the probability that a particular village is likely to perform highly if a minigrid is installed in it. It is part of the repository under the Lamwo Electrification Project by [Sunbird AI](https://github.com/SunbirdAI).

## Folder Structure

1. **[`compare_performance_of_ml_algorithms.ipynb`](#compare_performance_of_ml_algorithms)**  
   Trains and compares four models—XGBoost, polynomial regression (degree 2), linear regression, and random forest and evaluates them using leave-one-out cross-validation (LOOCV). See comments in the notebook for details.
   

2. **[`train_random_forest_regressor.ipynb`](#train_random_forest_regressor)**  
   Trains a random forest regressor with feature importance profiling. See comments in the notebook for details.
   

2. **[`rank_candidate_mgs.ipynb`](#rank_candidate_mgs)**  
   Uses the trained random forest model to rank the candidate minigird villages. See comments in the notebook for details.
   

## Getting Started

### Prerequisites
- Python 3.8+
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `pickle`
- Install dependencies via:
  ```bash
  pip install -r requirements.txt
  ```

### Usage
Navigate to this folder and run the desired notebook. See individual READMEs for detailed instructions.

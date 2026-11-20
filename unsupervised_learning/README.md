# Regression Algorithms

Despite this folder's name, its notebooks cover **supervised regression**
algorithms. They introduce each method and demonstrate fitting models,
evaluating predictions, and (in some notebooks) visualizing results.

## Notebooks

| # | Notebook | Topic |
|---|---|---|
| 1 | [01_linear_regression.ipynb](./01_linear_regression.ipynb) | Simple linear regression |
| 2 | [02_multiple_linear_regression.ipynb](./02_multiple_linear_regression.ipynb) | Multiple linear regression |
| 3 | [03_polynomial_regression.ipynb](./03_polynomial_regression.ipynb) | Polynomial regression |
| 4 | [04_ridge_regression.ipynb](./04_ridge_regression.ipynb) | Ridge regression (L2 regularization) |
| 5 | [05_lasso_regression.ipynb](./05_lasso_regression.ipynb) | Lasso regression (L1 regularization) |
| 6 | [06_elastic_net.ipynb](./06_elastic_net.ipynb) | Elastic Net |
| 7 | [07_decision_tree_regressor.ipynb](./07_decision_tree_regressor.ipynb) | Decision tree regressor |
| 8 | [08_random_forest_regressor.ipynb](./08_random_forest_regressor.ipynb) | Random forest regressor |
| 9 | [09_support_vector_regression.ipynb](./09_support_vector_regression.ipynb) | Support vector regression (SVR) |
| 10 | [10_gradient_boosting_regressor.ipynb](./10_gradient_boosting_regressor.ipynb) | Gradient boosting regressor |
| 11 | [11_xgboost_regressor.ipynb](./11_xgboost_regressor.ipynb) | XGBoost regressor |
| 12 | [12_lightgbm_regressor.ipynb](./12_lightgbm_regressor.ipynb) | LightGBM regressor |
| 13 | [13_catboost_regressor.ipynb](./13_catboost_regressor.ipynb) | CatBoost regressor |
| 14 | [14_knn_regressor.ipynb](./14_knn_regressor.ipynb) | K-nearest neighbors regressor |
| 15 | [15_neural_network_regressor.ipynb](./15_neural_network_regressor.ipynb) | Neural network (MLP) regressor |

## Setup

Use Python 3 with Jupyter. From the repository root, install the common
dependencies and launch JupyterLab:

```bash
python -m pip install jupyterlab numpy pandas matplotlib scikit-learn
jupyter lab
```

The XGBoost, LightGBM, and CatBoost notebooks also require their respective
packages:

```bash
python -m pip install xgboost lightgbm catboost
```

Open a notebook in JupyterLab and run its cells from top to bottom. Some
examples use scikit-learn datasets, including California Housing, which may be
downloaded the first time it is fetched.

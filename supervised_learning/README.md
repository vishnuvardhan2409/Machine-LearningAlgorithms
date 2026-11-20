# Supervised Learning

This folder contains Jupyter notebooks demonstrating supervised classification
algorithms. The examples introduce each method, explain its core ideas, and
apply it to built-in scikit-learn datasets or generated data.

## Notebooks

| # | Notebook | Topic |
|---|---|---|
| 1 | [01_logistic_regression.ipynb](./01_logistic_regression.ipynb) | Binary and multiclass logistic regression |
| 2 | [02_k_nearest_neighbors.ipynb](./02_k_nearest_neighbors.ipynb) | K-nearest neighbors (KNN) |
| 3 | [03_decision_tree_classifier.ipynb](./03_decision_tree_classifier.ipynb) | Decision trees |
| 4 | [04_random_forest_classifier.ipynb](./04_random_forest_classifier.ipynb) | Random forests |
| 5 | [05_support_vector_machine.ipynb](./05_support_vector_machine.ipynb) | Support vector machines (SVM) |
| 6 | [06_naive_bayes.ipynb](./06_naive_bayes.ipynb) | Naive Bayes |
| 7 | [07_gradient_boosting.ipynb](./07_gradient_boosting.ipynb) | Gradient boosting |
| 8 | [08_xgboost.ipynb](./08_xgboost.ipynb) | XGBoost |
| 9 | [09_lightgbm.ipynb](./09_lightgbm.ipynb) | LightGBM |
| 10 | [10_catboost.ipynb](./10_catboost.ipynb) | CatBoost |
| 11 | [11_adaboost.ipynb](./11_adaboost.ipynb) | AdaBoost |
| 12 | [12_linear_discriminant_analysis.ipynb](./12_linear_discriminant_analysis.ipynb) | Linear discriminant analysis (LDA) |
| 13 | [13_quadratic_discriminant_analysis.ipynb](./13_quadratic_discriminant_analysis.ipynb) | Quadratic discriminant analysis (QDA) |
| 14 | [14_neural_networks_mlp.ipynb](./14_neural_networks_mlp.ipynb) | Multi-layer perceptron (MLP) |

## Setup

Use Python 3 with Jupyter. From the repository root, install the common
dependencies and launch JupyterLab:

```bash
python -m pip install jupyterlab numpy pandas matplotlib scikit-learn
jupyter lab
```

The XGBoost, LightGBM, and CatBoost notebooks also require their respective
packages. Install them to run those examples:

```bash
python -m pip install xgboost lightgbm catboost
```

Open a notebook in JupyterLab and run its cells from top to bottom. Each
notebook can be explored independently.

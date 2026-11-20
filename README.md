# Machine Learning Algorithms

This repository is a personal, hands-on collection of Jupyter notebooks for
learning and demonstrating machine learning algorithms. The notebooks combine
conceptual explanations with Python examples, and are intended for study and
experimentation.

## Repository contents

| Folder | Contents |
|---|---|
| [`supervised_learning/`](./supervised_learning/) | Classification examples, including logistic regression, KNN, decision trees, random forests, SVM, Naive Bayes, boosting, discriminant analysis, and MLP. See the [folder guide](./supervised_learning/README.md). |
| [`unsupervised_learning/`](./unsupervised_learning/) | Regression examples, including linear and regularized regression, tree-based methods, SVR, boosting, KNN, and MLP. **Despite the folder name, these notebooks cover supervised regression, not unsupervised learning.** See the [folder guide](./unsupervised_learning/README.md). |
| [`reinforcement_learning/`](./reinforcement_learning/) | Dynamic programming and Monte Carlo methods for reinforcement learning. See the [folder guide](./reinforcement_learning/README.md). |

Each folder guide links to the notebooks in that topic. Most examples use
scikit-learn's built-in datasets or generated data; some dataset-fetching
examples may need an internet connection the first time they run.

## Getting started

### Requirements

- Python 3
- JupyterLab (or another Jupyter notebook interface)
- NumPy, pandas, Matplotlib, and scikit-learn for the main examples

The XGBoost, LightGBM, and CatBoost notebooks additionally need their
corresponding packages.

### Install and launch

From the repository root, install the common dependencies and start JupyterLab:

```bash
python -m pip install jupyterlab numpy pandas matplotlib scikit-learn
jupyter lab
```

To run the XGBoost, LightGBM, and CatBoost examples, install those libraries too:

```bash
python -m pip install xgboost lightgbm catboost
```

In JupyterLab, open a notebook and run its cells from top to bottom. Notebooks
are designed to be explored independently; start with the numbered examples
within a folder if you want to follow a topic in sequence.

## Notes

- There is no single project-wide requirements file; install dependencies for
  the notebooks you plan to run.
- The `unsupervised_learning` folder name is retained for now, but its current
  contents are regression algorithms. Regression is a supervised-learning
  task.

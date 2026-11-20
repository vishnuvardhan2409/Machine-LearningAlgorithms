# Reinforcement Learning

This folder contains Jupyter notebooks introducing foundational
reinforcement-learning methods. The examples are organized into two series:
dynamic programming methods for known environment models, and Monte Carlo
methods that learn from sampled episodes.

## Dynamic Programming

| # | Notebook | Topic |
|---|---|---|
| 1 | [01_policy_evaluation.ipynb](./dynamic_programming/01_policy_evaluation.ipynb) | Iterative policy evaluation |
| 2 | [02_policy_improvement.ipynb](./dynamic_programming/02_policy_improvement.ipynb) | Policy improvement |
| 3 | [03_policy_iteration.ipynb](./dynamic_programming/03_policy_iteration.ipynb) | Policy iteration |
| 4 | [04_value_iteration.ipynb](./dynamic_programming/04_value_iteration.ipynb) | Value iteration |
| 5 | [05_modified_policy_iteration.ipynb](./dynamic_programming/05_modified_policy_iteration.ipynb) | Modified policy iteration |

## Monte Carlo

| # | Notebook | Topic |
|---|---|---|
| 1 | [01_monte_carlo_prediction.ipynb](./monte_carlo/01_monte_carlo_prediction.ipynb) | Monte Carlo prediction |
| 2 | [02_first_visit_monte_carlo.ipynb](./monte_carlo/02_first_visit_monte_carlo.ipynb) | First-visit Monte Carlo |
| 3 | [03_every_visit_monte_carlo.ipynb](./monte_carlo/03_every_visit_monte_carlo.ipynb) | Every-visit Monte Carlo |
| 4 | [04_monte_carlo_control.ipynb](./monte_carlo/04_monte_carlo_control.ipynb) | Monte Carlo control |
| 5 | [05_on_policy_mc_control.ipynb](./monte_carlo/05_on_policy_mc_control.ipynb) | On-policy control with epsilon-greedy exploration |
| 6 | [06_off_policy_mc_control.ipynb](./monte_carlo/06_off_policy_mc_control.ipynb) | Off-policy Monte Carlo control |
| 7 | [07_weighted_importance_sampling.ipynb](./monte_carlo/07_weighted_importance_sampling.ipynb) | Weighted importance sampling |
| 8 | [08_monte_carlo_exploring_starts.ipynb](./monte_carlo/08_monte_carlo_exploring_starts.ipynb) | Monte Carlo control with exploring starts |

## Setup

Use Python 3 with Jupyter. From the repository root, install the dependencies
and launch JupyterLab:

```bash
python -m pip install jupyterlab numpy matplotlib
jupyter lab
```

Open a notebook and run its cells from top to bottom. The examples can be
explored independently.

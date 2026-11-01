# Gaussian Mixture Model Estimation with Expectation–Maximization

![NumPy](https://img.shields.io/badge/NumPy-from%20scratch-013243)
![Type](https://img.shields.io/badge/graduate%20coursework-UC%20Riverside-lightgrey)

This project implements a Gaussian-mixture data generator and the EM algorithm from scratch in NumPy, without library GMM routines. It studies how well EM recovers the true parameters, both when the number of components is known and when it is misspecified.

## Experiments

1. **Data generation.** Samples are drawn from a 3-component multivariate GMM with known weights, means and covariances.
2. **EM with the correct number of components.** The estimated weights, means and covariances are compared with the ground truth, and the true and estimated densities are plotted.
3. **EM with a misspecified number of components.** EM is rerun with K ≠ 3 to observe how the estimated parameters and fit change.
4. **Convergence.** Average negative log-likelihood and the estimated parameter values are tracked across iterations.

## Files

| File | Content |
|---|---|
| `EM.ipynb` | Implementation, experiments and plots |
| `EM_Report.pdf` | Write-up with results and observations |

## Run

```bash
pip install numpy scipy matplotlib
jupyter notebook EM.ipynb
```

# Sparse polynomial regression and LASSO

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lrhgit/sparse-polynomial-lasso/blob/main/sparse_polynomial_lasso_AAA.ipynb)

Interactive Jupyter notebook demonstrating multivariate polynomial
regression with OLS and LASSO. The notebook covers coefficient paths,
model sparsity, and selection of the regularization strength using
cross-validation.

The synthetic example is motivated by pressure-drop predictions from
AAA CFD simulations.

## Run locally

```bash
git clone https://github.com/lrhgit/sparse-polynomial-lasso.git
cd sparse-polynomial-lasso
python -m pip install numpy pandas matplotlib scikit-learn jupyterlab
jupyter lab
```

**Leif Rune Hellevik**  
Department of Structural Engineering, NTNU
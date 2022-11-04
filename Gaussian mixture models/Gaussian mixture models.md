# Gaussian mixture models

Implementation: scikit-learn Python library
```python
sklearn.mixture.GaussianMixture
```
Link: https://scikit-learn.org/stable/modules/generated/sklearn.mixture.GaussianMixture.html#sklearn.mixture.GaussianMixture.score_samples
<br>

## Theory
Gaussian mixture models (GMM) are probabilistic statistical models used to model datasets. <br>
This model assumes that all data points are generated from a mix of Gaussian distributions with unknown parameters. <br>
GMM is defined with mean vectors $\mu$ and covariance matrices $\Sigma$ for each variable present in the data. <br><br>

GMM are mostly used for:
- density estimation,
- clustering.
<br>

Procedure for fitting data points to GMM uses Expectation Maximization (EM) method. <br>

## Results
# Hyperparameters
The following two hyperparameters are used:
- number of Gaussian components for each variable in dataset (1 to 15),
- covariance matrix type: full, each component has its own general covariance matrix.

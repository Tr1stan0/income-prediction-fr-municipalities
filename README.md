<a name="readme-top"></a> <br />

<div align="center">
<h3 align="center">Data Science Project (Python)</h3>
  <p align="center">
    Median Income Prediction for French Municipalities
    <br />
    <a href="https://github.com"><strong>View Project on GitHub</strong></a>
    <br />
    <br />
    <a href="https://github.com/Tr1stan0/git-test/issues">Report Bug</a>
    ·
    <a href="https://github.com/Tr1stan0/git-test/issues">Request Feature</a>
  </p>
</div>

## About The Project

The goal of this project is to predict the median income of French municipalities using various supervised machine learning models. We leverage socio-demographic, geographic, and other municipal features to build regression models capable of estimating income distributions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Explanations

### Prerequisites

* Fork the project
* Clone the forked version:

  ```bash
  git clone https://github.com/your-username/income-prediction-fr-municipalities.git
  cd income-prediction-fr-municipalities
  ```

### Used methods

Several regression techniques were used and benchmarked using metrics like RMSE and R²:

* Linear Regression
* Ridge / Lasso Regression
* Decision Trees
* Random Forest
* Gradient Boosting (XGBoost, LightGBM, CatBoost)
* Stacking Regressors
* PCA for dimensionality reduction
* GridSearchCV and RandomizedSearchCV for hyperparameter optimization

Data preprocessing steps included:

* Encoding categorical features
* Scaling numerical features
* Handling missing values
* Feature engineering

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License
Distributed under the licence [LGPL-3.0](https://www.gnu.org/licenses/lgpl-3.0.html). See `LICENSE.txt` for more information.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---
# Model Selection Rationale

## Linear Regression

Linear Regression will be used as the baseline model because it is simple, fast and highly interpretable. It provides a reference against which more complex models can be compared.

## Decision Tree

Decision Trees can capture nonlinear relationships between agricultural variables such as rainfall, temperature, soil properties and crop type. However, individual trees can easily overfit.

## Random Forest

Random Forest is a strong candidate because it combines multiple decision trees and can model nonlinear relationships and feature interactions. It is particularly suitable for structured agricultural datasets containing weather, soil and crop-related variables.

## Gradient Boosting

Gradient Boosting is another high-priority candidate. It builds models sequentially and attempts to reduce prediction errors at each stage. It can provide strong performance on structured/tabular datasets but requires appropriate hyperparameter tuning.

## Final Selection

The final model will not be selected before evaluation. Random Forest and Gradient Boosting will be compared using the same validation procedure.

The final choice will consider:

* RMSE
* MAE
* R²
* Stability
* Generalization
* Interpretability
* Computational requirements

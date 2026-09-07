# Model Acceptance Criteria

A model will be considered suitable for further development when it satisfies the following conditions:

## Performance

* RMSE should improve over the baseline.
* MAE should remain within an acceptable agricultural decision range.
* R² should demonstrate useful explanatory power.

## Stability

The model should perform consistently across validation folds.

## Generalization

There should not be a major performance drop between validation and final testing.

## Bias

The model should not show severe systematic overprediction or underprediction.

## Explainability

Important model drivers should be documented.

## Scalability

The model should be computationally practical for the intended deployment environment.

## Final Decision

The model with the best overall balance of predictive performance, robustness, interpretability and operational feasibility will be selected.

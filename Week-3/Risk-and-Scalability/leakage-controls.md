# Data Leakage Controls

The following controls will be applied:

1. Keep the final test set untouched.
2. Use chronological train/validation/test splits when appropriate.
3. Fit preprocessing transformations only on training data.
4. Do not use post-harvest variables to predict harvest yield.
5. Record feature availability dates.
6. Avoid using future weather information unavailable at prediction time.
7. Perform feature engineering inside the training pipeline.
8. Review every feature for potential target leakage.

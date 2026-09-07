# Validation Strategy

## Data Segmentation

The initial planning target is:

* Training: approximately 70%
* Validation: approximately 15%
* Testing: approximately 15%

These percentages may be adjusted depending on dataset size.

## Time-Aware Validation

Agricultural data often contains observations from different years and seasons. Therefore, chronological validation is preferred when predicting future crop yields.

The model should learn from earlier observations and validate on later observations.

## Cross-Validation

TimeSeriesSplit or an expanding-window validation strategy can be used.

Example:

Training → Earlier Years
Validation → Later Year

Then:

Training → Earlier Years + Previous Validation Year
Validation → Next Year

## Test Set

The final test set must remain untouched during model selection and hyperparameter tuning.

It should be used only for the final unbiased evaluation.

## Geographic Validation

Where sufficient data exists, selected regions can also be held out to evaluate whether the model generalizes to locations not represented during training.

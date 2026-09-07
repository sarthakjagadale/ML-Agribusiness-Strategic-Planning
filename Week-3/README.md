# Week 3 – Model Development and Evaluation Planning

## Project

Machine Learning Integration in Agribusiness

## Objective

This week focuses on planning the development and evaluation of a machine learning model for agribusiness applications, with crop yield prediction selected as the primary use case.

## Main Activities

* Define the crop yield prediction problem
* Review suitable machine learning algorithms
* Compare regression and ensemble models
* Design training, validation and testing strategies
* Plan time-aware cross-validation
* Select appropriate evaluation metrics
* Develop a hyperparameter tuning strategy
* Identify data leakage risks
* Plan model improvement and scalability
* Conduct SWOT analysis

## Selected Model Approach

The proposed approach uses a baseline-to-advanced strategy:

1. Mean/Median Baseline
2. Linear Regression
3. Decision Tree
4. Random Forest
5. Gradient Boosting
6. Advanced boosting/deep learning as future scope

Random Forest and Gradient Boosting are the primary candidate ensemble models.

## Evaluation Metrics

The main regression metrics are:

* RMSE
* MAE
* R²

MAPE may be considered where percentage error is meaningful.

## Validation Strategy

Because agricultural data can be time-dependent, chronological validation and TimeSeriesSplit-style approaches are preferred over unrestricted random splitting.

## Expected Outcome

The outcome of Week 3 is a complete methodology for selecting, training, validating and evaluating a crop yield prediction model without actually implementing the model.

## Deliverables

* Model development plan
* Model selection rationale
* Data segmentation strategy
* Cross-validation strategy
* Evaluation metrics
* Risk analysis
* Scalability plan
* Model improvement roadmap
* SWOT analysis
* Professional Week 3 report

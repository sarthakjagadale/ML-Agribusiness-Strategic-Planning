# Risk Analysis

| Risk                         | Impact    | Mitigation                          |
| ---------------------------- | --------- | ----------------------------------- |
| Insufficient historical data | High      | Combine reliable data sources       |
| Temporal leakage             | Very High | Use chronological validation        |
| Geographic bias              | High      | Test unseen regions                 |
| Missing observations         | Medium    | Robust preprocessing                |
| Extreme weather              | High      | Stress testing and retraining       |
| Overfitting                  | High      | Cross-validation and regularization |
| Model drift                  | High      | Monitor performance and retrain     |
| Compute requirements         | Medium    | Start with efficient models         |
| Poor adoption                | High      | Use explainable outputs             |

## Major Risk

Temporal leakage is one of the most important risks because agricultural prediction involves time. Future information must never be allowed to influence a prediction intended for an earlier decision point.

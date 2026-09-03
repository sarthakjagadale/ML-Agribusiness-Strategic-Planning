# Missing Value Handling Strategy

## Why Missing Values Matter

Agricultural datasets may contain missing observations because of sensor failures, unavailable weather observations, incomplete surveys, reporting problems or differences in data collection.

## Detection

Calculate:

* Total missing values
* Missing percentage
* Missing values by column
* Missing values by crop
* Missing values by region
* Missing values by year

## Strategy

| Situation              | Strategy                                              |
| ---------------------- | ----------------------------------------------------- |
| Small numerical gaps   | Median/mean imputation                                |
| Categorical gaps       | Mode or Unknown                                       |
| Time-series gaps       | Carefully validated interpolation                     |
| Large missingness      | Investigate source or remove feature                  |
| Missing target         | Exclude from supervised training                      |
| Systematic missingness | Analyze cause and add missingness indicator if useful |

## Important Rule

Missing values should not be treated mechanically.

Before imputation, determine:

1. Why is the value missing?
2. Is missingness random?
3. Does missingness depend on region?
4. Does missingness depend on crop?
5. Can the original source provide the value?

## Quality Control

After treatment, compare the distribution before and after imputation to ensure that preprocessing has not introduced unrealistic patterns.

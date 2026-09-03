# Outlier Detection Strategy

## Objective

Identify unusual agricultural observations while distinguishing genuine extreme events from data errors.

## Methods

### IQR Method

Values below:

`Q1 - 1.5 × IQR`

or above:

`Q3 + 1.5 × IQR`

will initially be flagged for investigation.

### Z-Score

Used carefully for approximately normally distributed variables.

### Robust Methods

Median and Median Absolute Deviation (MAD) can be used for skewed or heavy-tailed agricultural variables.

### Domain Rules

Examples:

* Negative crop yield → investigate
* Negative rainfall → invalid
* Negative harvested area → invalid
* Extremely high yield → verify source
* Extreme rainfall → investigate whether it represents a genuine event

## Treatment

An outlier may be:

1. Retained
2. Corrected
3. Transformed
4. Capped/Winsorized
5. Removed with documented justification

## Important Principle

An extreme value is not automatically an error.

For example, an unusually low crop yield may represent a genuine drought or pest outbreak.

Therefore, statistical detection must be combined with agricultural domain knowledge.

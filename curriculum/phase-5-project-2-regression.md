# Phase 5: Milestone Project 2: Bulldozer Price Regression

**Days 39-46** (8 days)

Predict a numeric value from structured data that has dates; learn chronological splits and feature engineering.

**ZTM sections covered (as listed on the ZTM course page):** Milestone Project 2 (Supervised Learning: Time Series / Regression)

| Day | Focus | Python study (W3Schools, click to learn) | ZTM topics to watch |
| --- | --- | --- | --- |
| [39](../daily-lessons/day-39.md) | Project 2 (Bulldozer): problem and data | [Pandas Read CSV](https://www.w3schools.com/python/pandas/pandas_csv.asp), [Analyzing Data](https://www.w3schools.com/python/pandas/pandas_analyzing.asp) | Time-series regression problem definition; Data dictionary; Evaluation metric (RMSLE); Train / validation / test split by date |
| [40](../daily-lessons/day-40.md) | Project 2: dates and exploration | [Datetime](https://www.w3schools.com/python/python_datetime.asp), [Cleaning Wrong Format](https://www.w3schools.com/python/pandas/pandas_cleaning_wrong_format.asp) | Parsing dates when importing data; Sorting by date; Visualising sale price over time; Working on a sample for speed |
| [41](../daily-lessons/day-41.md) | Project 2: feature engineering with dates | [Fixing Wrong Data](https://www.w3schools.com/python/pandas/pandas_cleaning_wrong_data.asp), [Strings](https://www.w3schools.com/python/python_strings.asp) | Enriching features from the sale date: year, month, day, day of week; Dropping the original date column; Keeping a copy of the data |
| [42](../daily-lessons/day-42.md) | Project 2: turning data into numbers | [Cleaning Empty Cells](https://www.w3schools.com/python/pandas/pandas_cleaning_empty_cells.asp), [Casting](https://www.w3schools.com/python/python_casting.asp) | Converting strings to categories; Pandas category codes; Filling missing numeric values and adding indicator columns; Filling missing categorical values |
| [43](../daily-lessons/day-43.md) | Project 2: modelling with a chronological split | [ML Train/Test](https://www.w3schools.com/python/python_ml_train_test.asp), [Classes/Objects](https://www.w3schools.com/python/python_classes.asp) | Fitting a Random Forest regressor; Splitting into training and validation by date; Why random splits leak information from the future |
| [44](../daily-lessons/day-44.md) | Project 2: custom evaluation and faster experiments | [Functions](https://www.w3schools.com/python/python_functions.asp), [Math](https://www.w3schools.com/python/python_math.asp) | Custom RMSLE evaluation function; Scoring on training vs validation data; Training on a subset for faster experiments |
| [45](../daily-lessons/day-45.md) | Project 2: hyperparameter tuning | [ML Grid Search](https://www.w3schools.com/python/python_ml_grid_search.asp), [Lambda](https://www.w3schools.com/python/python_lambda.asp) | RandomizedSearchCV with limited iterations; Choosing hyperparameters for speed vs accuracy; Retraining the best model on all the data |
| [46](../daily-lessons/day-46.md) | Project 2: predictions, feature importance and review (Checkpoint 5) | [Pandas Plotting](https://www.w3schools.com/python/pandas/pandas_plotting.asp), [Matplotlib Bars](https://www.w3schools.com/python/matplotlib_bars.asp) | Preprocessing the test set the same way; Making predictions and the submission format; Feature importance; Project review |

## Assessments in this phase

- Day 46: [Checkpoint 5: Bulldozer Project](../assessments/checkpoint-5-bulldozer-project.md)

[Back to README](../README.md) | [Roadmap](../ROADMAP.md)

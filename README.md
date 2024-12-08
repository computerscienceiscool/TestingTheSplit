# TestingTheSplit

Testing several data splitting methods with the same input. This repository aims to explore how different split techniques work and their applications.

**⚠️ Work in Progress:** This project is under active development and needs refinement.

## Methods Explored

The following split methods are tested:

- **K-Fold**: Splits the dataset into `k` consecutive folds, with each fold used as a test set exactly once.
- **Shuffle Split**: Randomly shuffles and splits data into train/test sets for each iteration.
- **Group Shuffle Split**: Similar to Shuffle Split but ensures groups (e.g., related samples) are not split between train and test sets.
- **Group K-Fold**: A variation of K-Fold that prevents groups from being split across folds.
- **Time Series Split**: Specifically designed for time-series data, ensuring train-test splits maintain chronological order.

## Project Status

- Initial tests completed for all split methods.
- Work in progress to add comparison metrics and visualizations.
- Code refactoring and documentation improvements are underway.

## Contributions

Contributions are welcome! If you have suggestions or new ideas, feel free to open an issue or submit a pull request.

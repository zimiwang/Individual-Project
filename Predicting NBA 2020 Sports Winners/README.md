# NBA 2020 Winner Predictions Using Machine Learning

## Project Overview

This project aims to predict the outcomes of NBA games for the 2020 season by analyzing historical game data. Using a dataset that encompasses game results, team performance, and other relevant metrics, we apply both linear regression and random forests models to forecast game winners.

## Motivation

The drive behind this endeavor is to explore the predictive power of machine learning within the sports analytics domain. By examining the 2020 NBA season's games, the project seeks to uncover insights into team performance and game outcomes, potentially offering valuable information for fans, bettors, and team management.

## Project Workflow

### Data Collection
- Acquire game data from the NBA 2020 season and previous seasons for context.
- Preprocess data to structure and clean for analysis, including handling missing values and encoding categorical variables.

### Exploratory Data Analysis (EDA)
- Perform EDA to understand data patterns, distributions, and relationships between variables.

### Feature Engineering
- Develop new features that could influence game outcomes, such as home team advantage, previous season performance, and cumulative wins within the season.

### Model Building
- Implement a linear regression model to establish a baseline for prediction accuracy.
- Employ a random forests model for its ability to handle nonlinear relationships and interactions between features.

### Model Evaluation and Optimization
- Evaluate model performance using accuracy metrics and adjust parameters to optimize predictions.
- Compare models to determine the best performer based on predictive accuracy.

### Conclusion
- Summarize model performance, highlighting key findings and the most predictive features.

## Technical Details

- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **Data Source:** Basketball-reference.com for NBA game and team statistics
- **Models Used:** Linear Regression, Random Forests

## Getting Started

The project is structured as a Jupyter Notebook, providing a step-by-step guide through data preprocessing, model building, and analysis. To replicate or explore the project:
1. Clone the repository to your local machine.
2. Ensure you have Python and Jupyter installed, along with the required libraries.
3. Open the `Project_Wang.ipynb` notebook in Jupyter to view the analysis.

## Future Work

Potential directions for further exploration include:
- Incorporating player performance data to refine predictions.
- Exploring more sophisticated models or deep learning techniques.
- Analyzing the impact of external factors, such as player injuries or mid-season trades.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to basketball-reference.com for providing the dataset.
- Appreciation for Dr. Kerby for guidance and insights throughout the project's conception and execution.

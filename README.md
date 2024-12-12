# Hyperparameter Tuning with GridSearchCV and RandomizedSearchCV

This project demonstrates hyperparameter tuning using **GridSearchCV** and **RandomizedSearchCV** on a **RandomForestClassifier** model, applied to the **Iris dataset**.

## Project Overview
- **Objective**: Optimize a RandomForestClassifier model using hyperparameter tuning techniques.
- **Techniques Used**:
  - **GridSearchCV**: Exhaustive search through a predefined grid of hyperparameters.
  - **RandomizedSearchCV**: Random sampling of hyperparameter combinations from specified distributions.
- **Dataset**: Iris dataset with features like sepal length, sepal width, petal length, and petal width, used to classify iris flower species.
- **Goal**: Identify the best hyperparameter configurations to improve model performance.

## Steps Involved
1. **Import Required Libraries**: Import necessary libraries for data processing and model evaluation.
2. **Load and Prepare Dataset**: Load the Iris dataset and split it into training and testing sets.
3. **Define Model**: Initialize a RandomForestClassifier.
4. **Hyperparameter Tuning**:
   - Perform tuning using **GridSearchCV** to exhaustively search for the best hyperparameters.
   - Use **RandomizedSearchCV** for faster, random sampling of hyperparameters.
5. **Evaluate Models**: Compare the performance of the best models from both methods using classification reports.

## Requirements
- Python 3.x
- `scikit-learn`
- `numpy`
- `pandas`
- `scipy`

## How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script to execute hyperparameter tuning and model evaluation.

This project helps in understanding how to apply hyperparameter tuning to optimize machine learning models efficiently.
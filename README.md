# MLflow-project

This project demonstrates how to use the ElasticNet regression model to predict wine quality based on various chemical properties. It also incorporates MLflow for experiment tracking, model logging, and model registry.

## Project Structure

train.py: Python script for training the ElasticNet model, evaluating its performance, and logging the results to MLflow.

## Data

The project uses the Wine Quality dataset from the UCI Machine Learning Repository. The dataset contains information on various physicochemical properties of red wines, along with a quality score.

## Model

The model used is ElasticNet, a linear regression model with combined L1 and L2 regularization. This helps prevent overfitting and improves generalization to new data.

## How to Run

- Install the required packages: pip install -r requirements.txt
- Run the training script: python train.py [alpha] [l1_ratio]
- alpha: Regularization strength (default: 0.5)
- l1_ratio: Mixing parameter between L1 and L2 penalty (default: 0.5)

## Results

The script will output the evaluation metrics (RMSE, MAE, R2) for the trained model. These metrics, along with the parameters and the model itself, will be logged to MLflow.

Overview:

This project implements a neural network model to predict outcomes for a debutanizer process. The model evaluates its performance using metrics such as Root Mean Square Error (RMSE) and R² (Coefficient of Determination).	

Features:

Model Loading: Load the best model state using model.load_state_dict.
Evaluation: Evaluate the model on test data using RMSE and R² metrics.
Torch Integration: Utilizes PyTorch for model training and evaluation.

How to Run
Clone the repository.
Install dependencies:
Run the notebook file Rmse_Debutanizer.ipynb in Jupyter Notebook or VS Code.
Output
The model outputs:

Test RMSE: A measure of prediction error.
Test R²: A measure of how well the model explains the variance in the data.

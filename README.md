# screen_test_project
Screen Test Regression Model

1. Load configurations dynamically from an RTF-based JSON file.

2. Intelligent handling of missing values (mean imputation, custom fill values, etc.).

3. Feature generation: Linear, polynomial, and explicit pairwise feature interactions.

4. Automatic encoding for categorical variables.

5. Feature reduction using:

6. Tree-based model feature importance (Random Forest)

7. Principal Component Analysis (PCA)

8. Model selection based on configuration.

9. Hyperparameter tuning using GridSearchCV with TimeSeriesSplit.

10. Visual performance evaluation with:

11. Residual plots

12. Prediction vs Actual plots

13. Feature importance plot (if applicable)

14. Final metrics: RMSE, MAE, and R2 Score.


# Technologies Used

- Python 

- pandas

- numpy

- scikit-learn

- seaborn

- matplotlib

- striprtf
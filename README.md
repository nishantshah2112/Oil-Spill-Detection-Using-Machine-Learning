Oil Spill Detection Using Machine Learning

This project uses satellite image-derived data to detect oil spills in ocean patches. It involves cleaning and preprocessing the dataset, applying machine learning techniques, and evaluating models for accurate prediction of oil spill occurrences. The project also demonstrates saving and reusing the best-performing model.


---

Table of Contents

About the Dataset

Project Workflow

Technologies Used

Key Insights

Machine Learning Models

Results

Future Enhancements



---

About the Dataset

The dataset contains satellite image features split into patches. These patches are classified into two categories:

1. Non-Spill: No oil spill (majority class).


2. Oil Spill: Contains oil spill (minority class).



Key Points:

The dataset has 50 columns, where the target column represents the classification label.

Dataset source: Preprocessed satellite images processed via computer vision.



---

Project Workflow

1. Data Cleaning and Preprocessing

Imputation for missing values.

Data standardization and scaling.

Feature exploration and correlation analysis.



2. Exploratory Data Analysis (EDA)

Target class distribution.

Statistical summaries of features.

Insights derived from feature importance.



3. Machine Learning Pipeline

Implementation of Bagging and Ensemble techniques.

Comparison of various machine learning models.

Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix.



4. Model Saving and Reuse

Save the best-performing model.

Load and use the saved model for predictions on new data.



5. Predictions

Generate predictions for a random subset of the dataset.





---

Technologies Used

Programming Language: Python

Libraries:

Data Preprocessing: pandas, numpy, scikit-learn

Visualization: matplotlib, seaborn

Machine Learning: scikit-learn

Model Saving: joblib




---

Key Insights

Class Distribution: There is a significant class imbalance, with Non-Spill being the majority.

Feature Correlation: Identified top features correlated with the target variable.

Model Performance: Random Forest and BaggingClassifier yielded the highest accuracy and F1 scores.



---

Machine Learning Models

1. BaggingClassifier:

Aggregates predictions from multiple base learners.

Provides robust results for imbalanced datasets.



2. Random Forest:

Combines multiple decision trees.

High performance for classification tasks.





---

Results


---

Future Enhancements

Address class imbalance using SMOTE or other resampling techniques.

Experiment with deep learning models like CNN for better accuracy.

Automate hyperparameter tuning using GridSearchCV or Optuna.



---

Contributing

Contributions are welcome! Please fork the repository and create a pull request for any improvements.


---

License

This project is licensed under the MIT License. See the LICENSE file for details.


---

Contact

If you have any questions or feedback, feel free to reach out:

Author: Nishant Shah

Email: nishantshah2195@gmail.com

GitHub: nishantshah2112

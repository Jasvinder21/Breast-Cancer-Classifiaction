# Breast-Cancer-Classifiaction

This project involves the comparison and evaluation of various machine learning models for the classification of breast cancer. The goal is to predict whether a tumor is benign or malignant based on several features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

## Models and Performance

The following models were trained and evaluated, with their accuracy scores listed below:

| Model                                   | Accuracy   |
|-----------------------------------------|------------|
| **SVC**                                 | 0.982456   |
| **Gradient Boosting Classifier**         | 0.982456   |
| **Stochastic Gradient Boosting Classifier** | 0.982456   |
| Random Forest Classifier                | 0.973684   |
| Voting Classifier                       | 0.973684   |
| Logistic Regression                     | 0.964912   |
| SGD Classifier                          | 0.964912   |
| K-Nearest Neighbors (KNN)               | 0.956140   |
| Decision Tree Classifier                | 0.938596   |

### Key Observations
- **SVC, Gradient Boosting Classifier, and Stochastic Gradient Boosting Classifier** achieved the highest accuracy of 98.2%.
- **Random Forest and Voting Classifier** also performed well, with accuracy scores of 97.4%.
- **Logistic Regression and SGD Classifier** had similar performance, each scoring 96.5%.
- The **Decision Tree Classifier** had the lowest accuracy, indicating that more complex models may better capture the nuances in the data.

## Repository Structure
- `data/`: Contains the dataset and any data preprocessing scripts.
- `models/`: Includes the code for training and evaluating the models.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model experimentation.
- `results/`: Stores the performance metrics and visualizations.

## Conclusion
This project highlights the effectiveness of ensemble methods and support vector machines in classifying breast cancer with high accuracy. Future work could explore hyperparameter tuning, feature selection, and the application of deep learning techniques.

---

You can expand or modify this template based on the specifics of your implementation.

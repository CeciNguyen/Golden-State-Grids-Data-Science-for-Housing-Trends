# Golden State Grids: Data Science for Housing Trends
## **Project Overview**
This project explores various **supervised learning classification techniques** to predict a target variable using machine learning models. The analysis includes **exploratory data analysis (EDA), model training, evaluation, and comparison** to determine the best-performing model.

## **Dataset Overview**
- The dataset consists of multiple features that influence the target variable.
- Preprocessing steps include handling missing values, data type conversion, and feature scaling.
- The dataset is split into training and testing sets to ensure reproducibility and fair model evaluation.

## **Project Structure**
- `exploratory_data_analysis.ipynb` – Performs EDA, visualizations, and data preprocessing.
- `classification_models.ipynb` – Implements various classification models and evaluates their performance.
- `model_evaluation.ipynb` – Generates performance metrics and confusion matrices for model comparison.
- `README.md` – Project description and guide.

## **Models Used**
The following classification models were trained and optimized:
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **AdaBoost Classifier**

## **Performance Metrics**
Each model was evaluated using:
- **Accuracy**
- **Precision, Recall, and F1-score**
- **AUC-ROC Score**
- **Confusion Matrix**

## **Findings & Recommendations**
- **Random Forest performed strongly**, achieving high accuracy and AUC-ROC scores.
- **Stacking Classifier showed the best overall performance**, combining multiple models for improved predictions.
- **Decision Tree and AdaBoost provided competitive results**, with trade-offs in accuracy and computational efficiency.
- **KNN underperformed compared to other models**, indicating it may not be the best fit for this dataset.


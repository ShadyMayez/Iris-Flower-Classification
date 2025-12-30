# Iris Flower Classification

## Project Overview and Purpose
This project implements multiple supervised learning models to classify Iris flowers into three species: Setosa, Versicolor, and Virginica. Using the famous Iris dataset, the project explores feature selection and model comparison to identify the most accurate approach for biological classification based on petal and sepal dimensions.

## Key Technologies and Libraries
- **Language**: Python
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn`, `xgboost`

## Methodology and Workflow
### Data Preparation
1. **Loading**: Utilized the `sklearn.datasets.load_iris()` dataset.
2. **EDA**: Conducted descriptive statistics and visualization (correlation heatmaps, pairplots) to understand feature relationships.
3. **Feature Selection**: Explored techniques like `SelectKBest` and Recursive Feature Elimination (`RFE`) to identify the most predictive features.
4. **Scaling**: Applied `StandardScaler` to normalize feature ranges for distance-based models.

### Evaluated Models
The project implements a wide range of classifiers for comparison:
- **Logistic Regression**
- **Support Vector Classifier (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**
- **XGBoost Classifier**


## Results and Insights
- **Performance**: The project includes detailed classification reports (precision, recall, F1-score) and accuracy scores for each model.
- **Visualization**: Decision boundaries are visualized to show how different models partition the feature space.
- **Key Finding**: Due to the clear separation of species in the feature space (especially Setosa), most models achieve very high accuracy (>95%).

## How to Run
1. Install the required libraries:
   ```bash
   pip install -r requirements.txt

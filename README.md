# Iris-Machine-Learning-Project
This project explores the **Iris flower dataset**, a classic dataset in machine learning, to build a classifier that predicts the species of an iris flower based on its measurements.
- **Goal**: Predict the species (*Setosa*, *Versicolor*, *Virginica*) from sepal length, sepal width, petal length, and petal width.
- **Approach**:

## Project Overview
  1. **Exploratory Data Analysis (EDA)**  
     - Viewed dataset shape, distributions, and summary statistics.  
     - Visualized data with boxplots, histograms, and scatter matrices.  
  2. **Algorithm Comparison**  
     - Evaluated 6 algorithms (Logistic Regression, LDA, KNN, Decision Tree, Naive Bayes, SVM) using 10-fold cross-validation.  
     - Compared accuracy across models.  
  3. **Model Training and Prediction**  
     - Trained a Support Vector Machine (SVM).  
     - Evaluated using accuracy, confusion matrix, and classification report.
    
## Files in Repo
- `iris_data_overview.py` ->  Dataset structure, summary stats, and class distribution.  
- `iris_data_plots.py` -> Visualizations (boxplots, histograms, scatter plot matrix).  
- `iris_model_comparison.py` -> Accuracy comparison of six algorithms.  
- `iris_evaluation.py` -> Trains and evaluates an SVM classifier.

## Results
- Best performing model in this run: **SVM** with high accuracy (>98%).  
- Visualization confirmed petal measurements are the strongest predictors of species.


## What I learned
-  How to load and explore datasets with pandas.  
- Basics of visual exploratory data analysis with matplotlib.  
- How to evaluate multiple ML algorithms with scikit-learn.  
- How to train, predict, and assess a supervised learning model.

## Next steps
- Try additional models  
- Explore feature importance
- Utilize new skills in a more practical dataset

## How to Run
- pip install pandas matplotlib scikit-learn
- python iris_visualization.py
- python iris_plots.py
- python iris_algorithm_comparison.py
- python iris_predictions.py

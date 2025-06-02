AIML Internship Task 5 – Decision Trees & Random Forests

Objective:
To implement Decision Tree and Random Forest classifiers, visualize the tree, compare accuracies, and evaluate feature importance using a heart disease dataset.

Dataset:
The dataset contains medical information like age, cholesterol, blood pressure, etc., and whether a person has heart disease (1) or not (0).

What I Did:
- Loaded the dataset and explored correlations between features.
- Trained a Decision Tree and evaluated its accuracy.
- Visualized the decision tree structure.
- Tuned max_depth to avoid overfitting.
- Trained a Random Forest model and compared its accuracy with the decision tree.
- Displayed the most important features using Random Forest.
- Used cross-validation to check average accuracy.

Tools Used:
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

Output:
Both models worked well. Random Forest gave better accuracy and more stable results. Feature importance helped understand which columns affected predictions the most.

Files in this Repo:
- `Task_5_DecisionTree_RandomForest.ipynb`
- `heart.csv`

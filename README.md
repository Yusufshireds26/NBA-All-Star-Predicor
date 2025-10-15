NBA All-Star Predictor
Predict whether an NBA player will be selected as an All-Star based on player statistics and performance metrics. Built with Python, Pandas, Scikit-Learn, and Matplotlib/Seaborn for data processing, modeling, and visualization.

Key Features
Predicts NBA All-Star status using player performance and attributes.
Handles categorical data such as player position with OneHotEncoder.
Classification modeling using Logistic Regression and Random Forest.
Provides insights into which player stats most influence All-Star selection.
Tools & Libraries
Python – Programming language
Pandas – Data cleaning & manipulation
NumPy – Numerical computations
Scikit-Learn – Machine learning modeling, including Logistic Regression, Random Forest, OneHotEncoder, Train-test split, and Model Evaluation
Matplotlib / Seaborn – Data visualization
Key Steps
Load and clean NBA player dataset
Create target variable is_all_star based on points per game and performance metrics
Preprocess features: scale numeric variables and encode categorical variables
Train Logistic Regression and Random Forest classifiers
Evaluate model performance using accuracy, precision, recall, and F1-score
Visualize feature importance, class distributions, and model predictions
Insights
Player stats such as points, assists, rebounds, and position are strong predictors of All-Star status
Certain positions (Guard, Forward) show higher variance in selection likelihood
Model helps highlight emerging talent and potential breakout players
Project Structure
notebooks/ — Jupyter notebooks with analysis
scripts/ — Python scripts exported from notebooks
results/ — Generated plots, metrics, and reports
data/ — Raw NBA player dataset
Results
Classification metrics (Accuracy, Precision, Recall, F1-score)
Feature importance visualizations
Predicted vs actual All-Star selections
About
Predict NBA All-Star selections using player statistics with machine learning. Focuses on classification, data preprocessing, and insight-driven visualizations to understand key drivers behind All-Star selection.

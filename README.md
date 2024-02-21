#Customer-Segmentation-Classification
This project centers around developing a Customer Segmentation Classification model for an automobile company planning market expansion. The aim is to predict customer segments (A, B, C, D) in new markets based on existing market behaviors. Challenges include handling missing data, exploring complex customer behaviors, and optimizing model performance.

#Objective:
Predict customer segments (A, B, C, D) for the automobile company's products in new markets using machine learning techniques, leveraging characteristics and behaviors.

#Challenges:
Missing Data: Addressing missing values in key features.
Behavioral Complexity: Analyzing intricate customer behaviors, including age, work experience, family size, spending score, and categorical features.
Model Optimization: Enhancing the classification model's performance for accurate predictions across customer segments.
Dataset & Data Fields:
The dataset contains customer information in the existing market, including age, gender, marital status, education, profession, work experience, family size, spending score, and de-identified categories. The goal is to train a model for predicting customer segments in new markets.

#Libraries Used:
pandas: Data manipulation and analysis.
numpy: Mathematical operations.
seaborn: Data visualization.
matplotlib.pyplot: Plotting graphs.

#Key Steps:
Data Loading and Preprocessing: Handled missing values, dropped irrelevant columns, and imputed values for key features.
Exploratory Data Analysis (EDA): Explored data through visualizations, analyzed distributions, and relationships between features.
Data Visualization: Plotted violin and count plots to visualize feature distributions and correlations with segmentation.
Feature Engineering: Created new features based on counts of 'Profession' and 'Var_1' values.
Data Encoding: Ordinally encoded 'Spending_Score' and mapped categorical features.
Label Encoding: Encoded the target variable 'Segmentation' using LabelEncoder.
Data Splitting: Split the dataset into training and testing sets.
Feature Scaling: Applied standardization using StandardScaler on numerical features.

#Model Evaluation:
Evaluated various classifiers (Gradient Boosting, SVM, KNN, Decision Tree, Naive Bayes, Random Forest) using default settings and hyperparameter tuning. Gradient Boosting outperformed others, achieving an accuracy of 0.53.

#Conclusion:
The Gradient Boosting Classifier is recommended for predicting customer segments in new markets, showcasing the highest accuracy and overall better performance. The best-performing segment is identified as Class 3 (Segment D) based on F1-Score.

#Best Practices:
Proper handling of missing data.
Thorough exploratory data analysis for insights.
Feature engineering for enhanced model performance.
Evaluation and comparison of multiple classifiers.

#Note: For detailed code and insights, refer to the Jupyter Notebook in the repository.

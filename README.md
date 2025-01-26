# Heart Disease Prediction
 
This project focuses on predicting heart disease using machine learning, starting with defining the problem as the need for early detection to save lives. A publicly available dataset containing patient information—such as age, gender, cholesterol levels, blood pressure, and ECG readings—was used for analysis. 

The data was preprocessed by handling missing values (using mean, median, or mode imputation), normalizing continuous variables (e.g., cholesterol and blood pressure), selecting relevant features using correlation analysis and recursive feature elimination, and splitting the dataset into training (70%), validation (15%), and testing (15%) sets.

 Various machine learning models were implemented, including Logistic Regression, Random Forest, Support Vector Machines (SVM), and Gradient Boosting, to evaluate their performance. Each model was trained, and hyperparameters were tuned using methods like RandomizedSearchCV and GridSearchCV. The models were assessed using metrics like accuracy , precision , recall , F1-score , and AUC-ROC . Among the tested models, SVM emerged as the best-performing algorithm, achieving the highest accuracy and balanced performance. The project underscores the potential of machine learning to enhance healthcare by providing reliable tools for early heart disease detection and clinical decision-making.

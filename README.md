Key Steps in the Project
	1.	Data Loading & Exploration:
	•	Reads customer data from IT_customer_churn.csv.
	•	Checks for missing values and duplicates, handling them appropriately.
	2.	Data Preprocessing:
	•	Encodes categorical variables using One-Hot Encoding (OHE).
	•	Splits data into features (X) and target (y), where “Churn” is the target variable.
	3.	Model Training:
	•	Uses K-Nearest Neighbors (KNN) as the classification model.
	•	Splits data into training (70%) and testing (30%) sets.
	4.	Model Evaluation:
	•	Predicts churn on the test set.
	•	Evaluates performance using accuracy score and classification report.

📈 Potential Improvements
	•	Try other models like Logistic Regression, Random Forest, or XGBoost.
	•	Perform feature scaling to improve KNN accuracy.
	•	Use hyperparameter tuning for better performance.
	•	Add more feature engineering based on customer behavior trends.

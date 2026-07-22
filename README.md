HOUSE PRICE PREDICTION

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📌 Project Objective:

The goal of this project was to build a Machine Learning model that can predict house prices based on factors such as location, property type, BHK, bathrooms, area, furnishing, parking, distance to metro, nearby schools and hospitals, and other property features.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔍 Project Workflow:

• Loaded and understood the dataset

• Performed data validation and Exploratory Data Analysis (EDA)

• Checked for missing values and duplicate records

• Preprocessed numerical and categorical features

• Applied appropriate encoding and scaling techniques

• Separated input features (X) and target variable (y)

• Split the data into training and testing sets using an 80:20 ratio

• Built a baseline KNN Regressor model

• Compared KNN with a Decision Tree Regressor

• Performed hyperparameter tuning using RandomizedSearchCV

• Evaluated model performance using MAE, RMSE, and R² Score

• Saved the trained model using Joblib

• Deployed the model using Streamlit for real-time predictions

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🤖 Machine Learning Models:

• K-Nearest Neighbors (KNN) Regressor

• Decision Tree Regressor

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ KNN Hyperparameter Tuning:

After tuning the KNN model using RandomizedSearchCV, the best configuration was:

• Number of Neighbors (K) = 13

• Distance Metric = Manhattan

• Weighting Method = Distance

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Model Performance:

• KNN Regressor: R² Score = 86.90%

• Decision Tree Regressor: R² Score = 89.11%



The Decision Tree Regressor performed better than the KNN Regressor on this dataset, achieving a higher R² score and lower prediction errors.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Tools & Technologies:

• Python

• Pandas

• NumPy

• Matplotlib

• Seaborn

• Scikit-learn

• Joblib

• Streamlit

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

💡 Key Learning:

This project helped me strengthen my understanding of the complete Machine Learning workflow — from data understanding and preprocessing to model building, hyperparameter tuning, evaluation, and deployment.
It also helped me understand the importance of comparing multiple models and selecting the best-performing model based on appropriate evaluation metrics.
I'm continuously learning and improving my skills in Data Analytics, Machine Learning, Python, and Data Visualization.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

👩‍💻 Author

Thoram Jagadeesh
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
⭐ If you found this project useful, consider giving the repository a Star on GitHub.

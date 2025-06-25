🧠 Suicide Risk Prediction with Random Forest
This project builds and evaluates a binary classification model to predict high suicide risk using demographic and socioeconomic indicators. It was developed as part of a hands-on lab in the Machine Learning for Data Analysis course from Johns Hopkins University on Coursera.

📊 Objective
Predict whether a given data entry represents a high suicide risk (> 20 suicides/100k population) based on features such as:

-Country
-Year
-Gender
-Age group
-Population
-GDP per capita
-Number of suicides
-And others

⚙️ Key Features
🔍 Exploratory Data Analysis (EDA) with seaborn and matplotlib

🧹 Data cleaning and preprocessing

🔁 Label encoding and feature scaling

📈 Correlation analysis to identify key predictors

🌲 Model training using Random Forest Classifier (scikit-learn)

🧪 Model evaluation with:

-Confusion Matrix
-Accuracy Score
-Classification Report
-Feature Importance analysis

🧠 Model
Algorithm: Random Forest Classifier
Library: scikit-learn
Target: Binary variable high_risk (1 if suicides_no > 20, else 0)

✅ Results
-Accuracy: 100% on the test set
-Precision, Recall, F1-score: All metrics show perfect classification
-Feature Importance: Identified variables with the highest impact on predictions

📂 Dataset
Dataset name: Suicide Rates.csv

Source: Preloaded on Coursera Jupyter environment (educational use)

⚠️ Ethical Note
This project is purely academic and educational. It does not aim to replace clinical diagnosis or decision-making in mental health. The dataset is public and simplified, and the model should not be used in real-world scenarios without rigorous validation and ethical oversight.

📎 How to Use
-Clone the repo
-Open and run the notebook in Jupyter
-Explore the code, run the model, and test modifications

🔗 Related
📘 Course on Coursera
www.linkedin.com/in/santiagobc53 
📁 Project Repository

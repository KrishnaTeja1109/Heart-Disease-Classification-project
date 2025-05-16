# Heart Disease Classification With Exploratory Data Analysis and Various Classifiers

This project is focused on predicting the presence of heart disease in patients using machine learning techniques. The goal is to assist healthcare professionals in making quick and data-driven decisions using patient information.

📁 Files Included
Heart_Disease_Prediction.ipynb – Jupyter Notebook containing data analysis, preprocessing, model training, evaluation, and results.

Patient_Info.csv – Dataset containing relevant patient data like age, gender, blood pressure, cholesterol, etc.

🧠 Objective
To build a predictive model that accurately classifies whether a patient has heart disease based on clinical and lifestyle parameters.

⚙️ Technologies Used
Python

Pandas, NumPy – Data manipulation and preprocessing

Matplotlib, Seaborn – Visualization

Scikit-learn – Machine learning models and evaluation

📊 Dataset Description
Each row in Patient_Info.csv represents a patient record. Key features include:

Age

Sex

ChestPainType

RestingBP (resting blood pressure)

Cholesterol

FastingBS (fasting blood sugar)

RestingECG (resting electrocardiographic results)

MaxHR (maximum heart rate achieved)

ExerciseAngina

Oldpeak

ST_Slope

HeartDisease (target variable: 1 = presence of heart disease, 0 = absence)

🧪 Models Trained
The following classification models were explored:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors

Support Vector Machine (SVM)

📈 Performance Metrics
Models were evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

📝 Results
[Insert model comparison table or mention the best-performing model]

[Example: Random Forest achieved the highest accuracy of 89%]

📌 How to Run
Clone this repository

Make sure you have Python and Jupyter Notebook installed

Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Open Heart_Disease_Prediction.ipynb and run all cells

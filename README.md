🚢 Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

Project Overview
This project explores the Titanic Disaster Dataset from Kaggle, focusing on data cleaning, handling missing values, exploratory data analysis (EDA), and visualization. We aim to uncover patterns in survival rates based on different features such as age, gender, ticket class, and embarkation port.

Dataset Description

The dataset consists of three files:

train.csv → Contains labeled data for model training (features + survival column).
test.csv → Contains unlabeled data for testing (without survival column).
gender_submission.csv → A sample submission file for Kaggle competition.
Columns in train.csv
PassengerId – Unique identifier for each passenger
Survived – Survival status (0 = No, 1 = Yes)
Pclass – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name – Passenger's full name
Sex – Gender (male/female)
Age – Age in years
SibSp – Number of siblings/spouses aboard
Parch – Number of parents/children aboard
Ticket – Ticket number
Fare – Passenger fare
Cabin – Cabin number (if available)
Embarked – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Project Workflow
1. Data Cleaning
Load the dataset and inspect missing values
Handle missing values (e.g., filling NaN in 'Age', 'Cabin', and 'Embarked')
Convert categorical variables to numerical format
2. Exploratory Data Analysis (EDA)
Understanding survival distribution
Analyzing survival based on class, gender, and age
Visualizing survival trends using Seaborn and Matplotlib
3. Data Preprocessing for ML (Optional)
Encoding categorical variables
Feature selection
Splitting data into training and testing sets
Key Findings
Women had a higher survival rate than men.
First-class passengers had a higher survival probability compared to second and third class.
Most passengers embarked from Southampton (S).
Fare price was a strong predictor of survival.
Installation & Setup
Prerequisites
Ensure you have the following installed:

Python 3.x
Pandas, NumPy, Matplotlib, Seaborn
Jupyter Notebook or Google Colab
Clone Repository
Run the following command in your terminal:

git clone https://github.com/your-github-username/titanic-analysis.git

Then navigate to the folder:

cd titanic-analysis

Install Dependencies
Run:

pip install -r requirements.txt

How to Run the Project
Open Titanic_EDA.ipynb in Jupyter Notebook or Google Colab.
Run all cells step-by-step.
Analyze the visualizations and insights.
Project Structure
data/
train.csv
test.csv
gender_submission.csv
Titanic_EDA.ipynb – Jupyter Notebook with analysis
requirements.txt – Required Python libraries
README.md – Project documentation
.gitignore – Ignore unnecessary files
Future Work
Train a Machine Learning Model (e.g., Logistic Regression, Random Forest).
Optimize feature engineering for better accuracy.
Deploy model as a web app using Flask or Streamlit.
Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request.
Found an issue? Open an issue in the repo!
License
This project is open-source and available under the MIT License.

Contact
Author: W V P S SRIRAJ
Email: wsriraj10@gmail.com
GitHub: https://github.com/wvpssriraj10

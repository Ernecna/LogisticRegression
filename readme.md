Diabetes Prediction using Logistic Regression

This project aims to develop a machine learning model capable of predicting whether individuals have diabetes based on certain features. The dataset originates from a large study conducted by the National Institute of Diabetes and Digestive and Kidney Diseases in the United States, specifically among Pima Indian women aged 21 and above in Phoenix, Arizona—the fifth-largest city in the state. The dataset includes 768 observations and 8 numerical independent variables. The target variable, "outcome," indicates the presence (1) or absence (0) of diabetes.

Features

Pregnancies: Number of pregnancies

Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skinfold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index (weight in kg/(height in m)^2)

DiabetesPedigreeFunction: Diabetes pedigree function (a function which scores likelihood of diabetes based on family history)

Age: Age in years

Outcome: Class variable (0 or 1) indicating if the patient has diabetes

Workflow

Exploratory Data Analysis (EDA): Understanding the dataset through visualizations and statistics.

Data Preprocessing: Cleaning and preparing the data for modeling.

Model Building & Prediction: Developing a logistic regression model to predict diabetes.

Model Evaluation: Assessing the model's performance using metrics like accuracy, precision, recall, and F1-score.

Model Validation: Applying holdout validation and 10-Fold Cross-Validation to ensure the model's effectiveness.

Prediction for A New Observation: Demonstrating how to use the model to predict a new case.

Technologies Used

Python: For all computational tasks.

Pandas and NumPy: For data manipulation.

Matplotlib and Seaborn: For data visualization.

Scikit-learn: For data preprocessing, model building, and evaluation.

Getting Started

To run this project, you need to have Python installed on your machine. Clone this repository, navigate to the project directory, and install the required dependencies:

Copy code

pip install -r requirements.txt

Execute the script with:

Copy code

python logistic\_regression.py

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

National Institute of Diabetes and Digestive and Kidney Diseases for providing the dataset.

Contributors who have helped in refining the model and documentation.

Feel free to customize the README based on your project's specific requirements or additional sections you'd like to include. ​

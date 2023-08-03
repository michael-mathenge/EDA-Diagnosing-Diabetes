# EDA-Diagnosing-Diabetes
This GitHub repository contains a data analysis project focused on diagnosing diabetes using a dataset with various medical predictor variables. The objective is to predict whether a patient has diabetes or not based on certain diagnostic measurements.

Dataset
The dataset used in this analysis comprises data from females of Pima Indian heritage who are at least 21 years old. It includes the following features:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration at 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure
SkinThickness: Triceps skinfold thickness
Insulin: 2-Hour serum insulin
BMI: Body mass index
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age (years)
Outcome: Class variable (0 or 1) representing the absence or presence of diabetes, respectively
Objectives
The main objectives of this data analysis project are:

Exploratory Data Analysis (EDA): Understand the dataset's characteristics, explore relationships between features, and gain insights into how the predictor variables relate to the target variable (Outcome).

Data Preprocessing: Handle missing values, outliers, and any necessary data transformations to prepare the dataset for modelling.

Model Development: Build machine learning models for binary classification to predict diabetes presence based on the provided medical measurements.

Model Evaluation: Evaluate the performance of the developed models using appropriate metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

Key Files
data/diabetes_data.csv: The raw data file containing the medical predictor variables and the target variable (Outcome).
notebooks/Data_Analysis_Diabetes.ipynb: Jupyter Notebook containing the step-by-step data analysis process, including EDA, data preprocessing, and model development.
models/: Directory to store the trained machine learning models.
results/: Directory to store evaluation results and visualizations.
Running the Notebook
To replicate the analysis, follow these steps:

Clone the repository to your local machine:
bash
Copy code
git clone <repository_url>
Install the required libraries listed in requirements.txt:
Copy code
pip install -r requirements[diabetes.csv](https://github.com/michael-mathenge/EDA-Diagnosing-Diabetes/files/12249284/diabetes.csv)
.txt
Open and run the Jupyter Notebook Data_Analysis_Diabetes.ipynb using Jupyter or JupyterLab.

The notebook will guide you through the data analysis process, including data loading, EDA, data preprocessing, model development, and evaluation.

Acknowledgements
The dataset used in this analysis is sourced from the National Institute of Diabetes and Digestive and Kidney Diseases. and was initially collected for research purposes.

[Uploading diabetes.csv…]()


https://www.kaggle.com/uciml/pima-indians-diabetes-database

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Feel free to use, modify, and extend this analysis for educational or research purposes. Any feedback or contributions are welcome!

For more details or inquiries, contact Michael Mwangi at mmathenge1@gmail.com.

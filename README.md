 Cancer Patient Survival Prediction Using Scikit-learn
This project uses machine learning to predict the survival status ("Alive" or "Dead") of cancer patients based on clinical features such as tumor size, age, cancer stage, and tumor grade.

 Features Used
Tumor Size (numeric)

Age (numeric)

Stage (1 to 4)

Grade (categorical, e.g., Grade_1, Grade_2, Grade_3, Grade_ anaplastic; Grade IV, etc.)

🛠 Technologies Used
Python

Pandas

NumPy

Scikit-learn (RandomForestClassifier)

Jupyter Notebook

 Dataset
The dataset contains records of cancer patients with relevant features and their survival outcome (Alive or Dead). The target variable is encoded using LabelEncoder.

 How It Works
Load and preprocess the dataset

One-hot encode categorical features

Train a RandomForestClassifier on the data

Accept user input for new patient details

Predict and display the survival status

BENKHELIFA ASSIA

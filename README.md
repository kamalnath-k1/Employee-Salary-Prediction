📊 Employee Salary Prediction
This project predicts whether an employee earns more than $50K per year based on demographic and work-related features using Machine Learning and Deep Learning models.

✅ Project Overview
Goal: Predict the income class (<=50K or >50K)

Dataset: UCI Adult Census Income dataset (adult 3.csv)

Models Used:

Random Forest Classifier (Machine Learning)

Neural Network built with Keras (Deep Learning)

Tools & Libraries: Python, pandas, scikit-learn, matplotlib, seaborn, TensorFlow/Keras

⚙ System Requirements
Python 3.7+

RAM: ≥ 8GB recommended

OS: Windows / Linux / MacOS

📦 Libraries Used
bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
🧪 Step-by-Step Procedure
Load and explore the dataset

Data preprocessing:

Handle missing values

Encode categorical variables with LabelEncoder

Scale numerical features

Perform Exploratory Data Analysis (EDA):

Histograms and count plots to understand feature distributions

Build and train models:

Random Forest classifier

Deep Learning model using Keras

Evaluate models:

Accuracy

Precision, recall, and F1-score

Compare model performance and draw conclusions

📊 Results
Model	Accuracy	F1-score (>50K class)
Random Forest	85%	0.66
Deep Learning	85%	0.63

Random Forest slightly outperforms Deep Learning in predicting high-income class.

✅ Conclusion
Both models achieve similar overall accuracy.

Random Forest provides slightly better recall & F1-score on the minority high-income class.

The dataset’s tabular nature favors traditional ML models.

# Salary-Estimation-Using-K-Nearest-Neighbors-KNN-
This project uses the salary.csv dataset to predict an individual's income class (<=50K or >50K) based on various attributes such as age, education, capital gain, and hours worked per week. The project employs the K-Nearest Neighbors (KNN) algorithm for classification and includes steps for data preprocessing and visualization.

Dataset:
The dataset used is salary.csv, which contains the following columns:

age: Age of the individual.
education.num: A numerical representation of the individual's education level.
capital.gain: The capital gains reported by the individual.
hours.per.week: The number of hours worked per week.
income: The income class, either <=50K or >50K.
Key Steps in the Project:
Data Loading: The dataset is loaded using Pandas, and initial exploration is performed to understand the data.

Data Preprocessing:

MinMax Scaling is applied to normalize the numerical features (age, education.num, capital.gain, and hours.per.week).
This ensures that all features contribute equally to the distance calculations in the KNN algorithm.
Visualization:

A correlation heatmap is created to visualize the relationships between the features. This helps identify strong or weak correlations, which can assist in feature selection or engineering.
K-Nearest Neighbors Algorithm:

The KNN algorithm is used to classify individuals into one of the two income classes (<=50K or >50K).
Distance metrics and neighbor counts are key parameters adjusted during the process.
Dependencies:
Python 3.x
Pandas: For data manipulation and loading.
NumPy: For numerical computations.
Matplotlib & Seaborn: For visualizing data and correlations.
scikit-learn: For scaling features and implementing the KNN algorithm.
Instructions to Run:
Clone the repository to your local machine.

The heatmap generated in the notebook helps in visualizing the correlation between different features. Features with a high correlation might contain redundant information, which can influence the model's performance.

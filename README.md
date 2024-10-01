# Salary-Estimation-Using-K-Nearest-Neighbors-KNN-
This project uses the salary.csv dataset to predict an individual's income class (<=50K or >50K) based on various attributes such as age, education, capital gain, and hours worked per week.<br>
The project employs the K-Nearest Neighbors (KNN) algorithm for classification and includes steps for data preprocessing and visualization.

## Dataset:
The dataset used is salary.csv, which contains the following columns:

age: Age of the individual.<br>
education.num: A numerical representation of the individual's education level.<br>
capital.gain: The capital gains reported by the individual.<br>
hours.per.week: The number of hours worked per week.<br>
income: The income class, either <=50K or >50K.<br>

## Key Steps in the Project:
Data Loading: The dataset is loaded using Pandas, and initial exploration is performed to understand the data.<br>

###Data Preprocessing:<br>
MinMax Scaling is applied to normalize the numerical features (age, education.num, capital.gain, and hours.per.week).<br>
This ensures that all features contribute equally to the distance calculations in the KNN algorithm.<br>

###Visualization:<br>
A correlation heatmap is created to visualize the relationships between the features. <br>
This helps identify strong or weak correlations, which can assist in feature selection or engineering.<br>

### K-Nearest Neighbors Algorithm:<br>
The KNN algorithm is used to classify individuals into one of the two income classes (<=50K or >50K).<br>
Distance metrics and neighbor counts are key parameters adjusted during the process.<br>

## Dependencies:
Python 3.x<br>
Pandas: For data manipulation and loading.<br>
NumPy: For numerical computations.<br>
Matplotlib & Seaborn: For visualizing data and correlations.<br>
scikit-learn: For scaling features and implementing the KNN algorithm.<br>

## Visualizations:<br>
The heatmap generated in the notebook helps in visualizing the correlation between different features.<br>
Features with a high correlation might contain redundant information, which can influence the model's performance.

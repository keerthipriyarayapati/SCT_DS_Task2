### SCT_DS_Task2

#### Project Title: Data Cleaning and Exploratory Data Analysis(EDA)

#### Description:
This repository contains the analysis of the Titanic dataset. The goal is to explore, clean, and visualize the dataset to understand key factors influencing passenger survival.

#### Objectives:
Load and explore the Titanic dataset

Handle missing data (Age, Cabin, Embarked)

Preprocess and clean the dataset

Perform exploratory data analysis (EDA)

##### Identify survival patterns based on:
-Gender

-Passenger class

-Age

-Fare

-Embarked port

#### Key Visualizations- by using Matplotlib and Seaborn
Survival count plot (Survived vs Died)

Survival by Gender

Survival by Passenger Class (Pclass)

Age distribution

Gender distribution

Age distribution by Survival

Fare distribution

Fare distribution by Survival

Correlation heatmap

Survival by Embarked Port

Survival by Family size

####  Data Cleaning Steps
Imputed missing Age values using median

Filled missing Embarked values using mode

Dropped Cabin column due to high missing values

Converted categorical variables into numeric formats where required

#### Key Findings
Gender: Females had higher survival rates than males

Passenger Class (Pclass): Higher-class passengers had better chances of survival

Fare: Higher fare correlated with higher survival probability

Age: Children and young adults had slightly higher survival rates

Embarked Port: Passengers from certain ports had higher survival

#### Tools and Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

#### Files in Repository

```SCT_DS_2_.ipynb``` — Complete code, analysis, and visualizations

requirements.txt

README.md

#### Requirements Install dependencies using: 
```pip install -r requirements.txt``` 
##### Recommended versions (for reproducibility):
pandas >= 1.5.0

numpy >= 1.25.0

seaborn >= 0.12.0

matplotlib >= 3.7.0

#### Dataset
1. Titanic Dataset on Kaggle
2. Ensure train.csv and test.csv are placed in the notebook folder before running the analysis
#### How to Run
1. Clone the Repository
``` ```
2. Install dependencies
```pip install -r requirements.txt```
3. Open ```SCT_DS_2.ipynb``` in Jupyter Notebook or Google Colab
4. Run each notebook cell sequentially

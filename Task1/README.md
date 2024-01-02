# CODSOFT

# Titanic Survival Prediction with 
![Image Alt Text](https://github.com/mercytegekson/CODSOFT/blob/main/Task1/Titanic.png)

# Titanic Survival Prediction

![Titanic](https://github.com/mercytegekson/CODSOFT/blob/main/Task1/Titanic-Dataset.csv)


## Problem statement
In the aftermath of the Titanic incident, where the ship tragically sank after colliding with an iceberg, our objective is to develop a predictive model for passenger survival. Leveraging various features such as demographic information, ticket class, and boarding location, our aim is to create a model that can estimate the likelihood of a passenger surviving the disaster. By analyzing and understanding the patterns within the dataset, we seek to contribute to the broader understanding of factors influencing passenger outcomes during this historic maritime event.
The project's aim is to:
•	Uncover meaningful patterns associated with Titanic Survival.
•	Create Machine Learning based predictive models that can show likelihood of a passenger survivig the Titanic incident.


## PROJECT OVERVIEW 
The project focuses on the creation of a machine-learning project for  Titanic Survival prediction.

## BUSINESS UNDERSTANDING
The Titanic incident stands as a pivotal event in maritime history, and its analysis presents a unique opportunity for our organization to employ predictive analytics to understand passenger survival dynamics. The objective is to develop models that predict the likelihood of survival based on various passenger attributes, shedding light on the factors influencing survival rates during maritime disasters.


## Components

* **Jupyter Notebook**
The [Jupyter Notebook](https://github.com/mercytegekson/CODSOFT/blob/main/Task1/index.ipynb)is our key deliverable and contains details of our approach and methodology, data cleaning, exploratory data analysis and model building and validation.

I recommend using [nbviewer](https://nbviewer.jupyter.org/) to view the Jupyter Notebook.


* **Data**

The dataset can be found in the file *"Titanic-Dataset.csv"* in the Data folder, in this repository. It was originally provided in the following [repository](https://github.com/mercytegekson/CODSOFT/blob/main/Task1/Titanic-Dataset.csv).

## Technologies/ Packages

* Python version: 3.6.9
* Matplotlib version: 3.1.3
* Seaborn version: 0.9.0
* Pandas version: 0.25.1
* Numpy version: 1.16.5
* Scikit-learn version: 0.21.2  

## To get started

1. Clone this repository - [guidance](https://help.github.com/articles/cloning-a-repository/).
2. Dataset can be found in the file"Titanic-Dataset.csv".
3. Check requirements in Technologies section above and download libraries if necessary.

## 1. Data Wrangling
Here we will work on data cleaning, handling missing values, data transformation, handling duplicates, data reshaping and other processes to ensure that we have a clean, structured, and suitable format for analysis and modeling

## 2. Exploratory Data Analysis (EDA)
Here we will explore the different features of the dataset to gain a better understanding of the data. We will use data vizualization to uncover trends and patterns. We will use Feature Engineering to create new features from existing ones and perform One-Hot Encoding on categorical variables that we will require for analysis.


## 3.Baseline model:Logistic Regression Model.
The model exhibits strong predictive performance for the majority class ("False") with high precision (82%), recall (85%), and F1-Score (83%). However, it faces challenges in accurately predicting instances of the minority class ("True"), reflected in lower precision (77%), recall (73%), and F1-Score (75%). This indicates potential difficulties in correctly identifying passengers who are likely to survive the incident.

## 4. KNN Model
### KNN Results
The KNN model achieves an accuracy of 70.3%, indicating its overall ability to correctly predict outcomes. In terms of precision, the model demonstrates a satisfactory ability to accurately identify passengers who will survive, with a precision of 68%. However, the recall is relatively lower at 54%, suggesting that the model might not capture all instances of actual survival. The F1-score, a balance of precision and recall, is at 60%. The classification report shows that the model performs better in identifying not survived instances ("False") than survived instances ("True").


## Conclusions
Although this model is reliable, it should be used in conjunction with other domain information for more precise prediction of passenger survival.













    


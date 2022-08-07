# AGRI-PRODUCE-OPTIMIZATION-ENGINE
## Context -
Precision agriculture is in trend nowadays. It helps the farmers to get informed decision about the farming strategy. Here, I present you a dataset which would allow the users to build a predictive model to recommend the most suitable crops to grow in a particular farm based on various parameters.
## Problem Statement -
Building a Predictive Model so as to suggest the most suitable crops to grow based on the available climatic and soil conditions.

<img align = "center" height = "300" width = "800" src = "https://user-images.githubusercontent.com/84726790/166432628-9aa89fd6-79aa-46a9-8484-f21887fb17d7.jpg">

## Technical aspect -
*  Python 3.9
*	Front-end: HTML, CSS
*	Back-end: Flask
*	IDE: Jupyter Notebook, Visual Studio

## How to run this app -
Code is written in Python 3.9. If you don't have python installed on your system, click here https://www.python.org/downloads/ to install.
* Create virtual environment - *conda create -n myenv python=3.9*
*	Activate the environment - *conda activate myenv*
*	Install the packages - *pip install -r requirements.txt*
*	Run the app - *python main.py*

# Workflow-
## Goal -
To achieve precision farming by optimizing the agricultural production.
The project is intended on Precision Farming.

➔ To Optimize Productivity

➔ By Understanding requirements of climatic and soil conditions for crops.

➔ Helps us to Cope up with weather unpredictability.
## About The Dataset Used (data.csv) -
The Dataset Consists of 22 Unique Crops such as Maize, Wheat, Mango, Watermelon, Mango etc.

➔ The dataset consists of climatic conditions required to grow the crops.

   ◆ Temperature, Humidity, Rainfall.
   

➔ The dataset also consists of soil conditions required to grow the crops

   ◆ N: The Ratio of Nitrogen Content in Soil.
   
   ◆ P: The Ratio of Phosphorus Content in Soil.
   
   ◆ K: The Ratio of Potassium Content in Soil.
   
   ◆ pH: pH of the Soil
   
   ## Libraries Used in This Project - 
   
● Numpy: Used for Mathematical Operations.

● Pandas: Used for DataFrame Operations.

● Seaborn and Matplotlib: Used for Data Visualizations.

● Ipywidgets: Used for Interactive Analysis.

● Sklearn: Used for Machine Learning Algorithms
   
   ## Data Collection -
   You can Download the data from here- [Click here](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
   
  ## Data Pre-processing -
  Here,in this dataset no need to pre-process the data, Here Data is already clean and free from missing value.
  
  ## Distribution of Graphs -
  <img align = "center" height = "300" width = "700" src = "https://user-images.githubusercontent.com/84726790/183288480-01fb439b-9ae8-4239-9462-aa51e29bf68b.png">

  ## Model Creation and Evaluation -
  * Here, I import Logistic Regression from sklearn.linear_model, fit my model, and make a predictive model.
  * Here, the code is not so complex but a question arises that why do we use Logistic Regression instead of Linear Regression?
 * That is because when we have to deal with continuous variables or we can say with numerical values we use linear regression but when we have to deal with categorical variables we use logistic regression . Here we are dealing with categorical variables that's why we used logistic regression.
 * Logistic Regression is trying to map real values or independent data points in the interval from 0 to 1.
 * Points below the cut off line belong to Class B and points above the cut off line belongs to class A
 * Points in class A have the probability of a certain occurrence on the other hand points in class B have no probability of a certain occurrence.

 ## Website Link -
 http://127.0.0.1:7368/
 
 


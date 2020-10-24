# ih_datamadpt0420_project_m3


# IRONHACK 
## Data Analysis Bootcamp - Project III - Kaggle Competition  
  
![Image](https://images.unsplash.com/photo-1457969414820-5fdd86fc0b84?ixlib=rb-1.2.1&auto=format&fit=crop&crop=entropy&w=1620&h=500&q=80)  

## Table of Contents  

* [About the Project](#about-the-project)  
  * [Challenge 1](#pushpin-challenge-1)  
  * [Challenge 2](#pushpin-challenge-2)  
  * [Built With](#hammer-built-with)  
* [Project Structure](#project-structure)  
  * [Dataset Analysis](#page_with_curl-dataset-analysis)  
  * [Tableau Report](#tableau-report)  
* [Next Stages](#next-stages) 
  
## About the project  
  
The aim of this repository is to show the adquire skills throught Module 13of Data Analytics in IronHack's Bootcamp [PT2020]  
To show our skills, we have participated in a kaggle competition where we predicted diamond's price from a given dataset. 


  
###  :pushpin:  **Challenge 1: Get the best prediction for diamonds_predict dataset**

The goal of this challenge is to build an **predictived algorithm** that will give as the most accurate price per diamonds. Previously, on module 2, we have analyzed the dataset and extrated insights for the train dataset. These are the previous insights:


   - Strong correlation between size features (X, Y, Z, Carat) and Price.
   - Price and carat are correlated
   - Carat has a logaritmic grow respect to size.
   - Best/lower features combinations are not the best/worst diamonds
   

 ###  :hammer: Built With   
The core of the project is Python 3.7.3, but you have to install those libraries for run the analysis.   
- [Pandas (v.0.24.2)](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)  
- [Numpy (v.1.18.1)](https://numpy.org/doc/stable/)  
- [Matplotlib(v.3.2.1)](https://matplotlib.org/)  
- [Seaborn(v.0.10.1)](https://seaborn.pydata.org/)  
- [Plotly(v.4.8.2)](https://plotly.com/)  
- [Lightgbm(2.3.0)]
- [scikit-learn(0.23.2)]
  
## **Project Structure**
###  **:page_with_curl:Dataset Analysis**  
The following structure has been followed to train and predict with the model selected. Before chose Lighgm, other Algorithms were tested as RandomForestRegressor or LinearRegressor.

```
## Index
- **Libraries used**
- **Dataset Analysis**
- **Data Cleaning and new variables**
- **Transform data**
- **Train supervised model**
- **HPredictions**

```
  
  
  
### :file_folder: **Folder structure**  
```
└── ih_datamadpt0420_project_m3  
    ├── __trash__  
    ├── .gitignore  
    ├── README.md  
    ├── notebooks  
    │   ├── diamonds_ml.ipynb  
    ├── data  
    │   ├── diamonds_predict.csv  
    │   ├── diamonds_train.csv  
    └── solutions_v2  

```  
  

 ---  
### ** Next stages**  

- Update notebook with deeper analysis per group. 
# Airbnb Seattle Analysis
<img src='wordcloud.png' width="400"> <img src="map.png" width="400">

## Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation
In this project, there are no requirements for libraries beyond the Anaconda distribution of Python.
The code is recommended to be run using Python version 3.*.

The libraries used:<br>
* numpy<br>
* pandas<br>
* matplotlib.pyplot<br>
* seaborn<br>
* folium<br>
* statsmodels.tsa<br>
* nltk<br>
* sklearn

## Project Motivation<a name="motivation"></a>
For this project, I was interested in exploring Airbnb listings, reviews, and pricing in Seattle.  
Proposed questions:
1. What are the peak times of the year to visit Seattle?
2. How does price change across the year? Is there any trend or seasonality?
3. How do customers feel about their stays in Seattle? Positive or negative? What are the keywords in their reviews?
4. Can we predict the price based on the host and room data?
5. What factors of homestays contribute to salary?

For question1-3, I conducted a comprehensive **exploratory data analysis(EDA)** on all the 3 datasets here to give an overview of price trend, sentiment keywords, and room distribution.
Visualization and descriptive analysis code can be found in `eda_utility.py`.
For question4&5, I conducted **predictive modeling** on the 'price' variable in `listing.csv` using linear regression model. Details can be found in `predictive_utility.py`.

## File Descriptions<a name="files"></a>
#### Datasets:
This project is an analysis on 3 `.csv` files about calendar, listings, and reviews respectively. You can find them in the `Seattle_data` folder. 
More descriptive information can be found [here](https://www.kaggle.com/airbnb/seattle?select=calendar.csv).

#### Coding:

There are two `.py` files and one notebook file available here to showcase work related to the above questions. The 2 utility `.py` files are functions deployed for EDA and predictive analysis.
For the whole workflow, results, and interpretation from a technical view, please refer to the `airbnb_analysis.ipynb`.

#### Results and Report:
Since interactive maps in the notebook don't work in Github repository, you may find the integrated notebook report 
rendered by nbviewer [here](https://nbviewer.jupyter.org/github/slwangit/airbnb_seattle_analysis/blob/main/airbnb_analysis.ipynb).
This is an organized report with results and interpretation from the analyst's point of view. 

## Results
The main findings and report can be found in the post available [here](https://medium.com/@slwang0507/how-do-customers-feel-about-their-stay-in-seattle-with-airbnb-20f41ec00223).
The article is friendly for the audience from many fields.

## Licensing, Authors, and Acknowledgements<a name="licensing"></a>
The datasets for this project was obtained from Kaggle. You can find licensing and other detailed information at the source link available [here](https://www.kaggle.com/airbnb/seattle?select=calendar.csv).
Also, I must give credit to Stack Overflow for the coding part and Medium for the statistical part. 
All the code here are open to the public. Thus, feel free to use it as you would like.

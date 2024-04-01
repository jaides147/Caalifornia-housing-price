
CALIFORNIA HOUSING PRICES IN 90S

This project aims to capture the average house price from the dataset which contains the the data of houses in California in 1990s.
For this project Regression techniques have been used in sklearn library.



## DATASET

Data Set Characteristics:

This dataset was obtained from the StatLib repository. https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html

The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset are provided per household, these columns may take surprisingly large values for block groups with few households and many empty houses, such as vacation resorts.

It can be downloaded/loaded using the :func:sklearn.datasets.fetch_california_housing function.

:Number of Instances: 20640

:Number of Attributes: 8 numeric, predictive attributes and the target

:Attribute Information:
    - MedInc        median income in block group
    - HouseAge      median house age in block group
    - AveRooms      average number of rooms per household
    - AveBedrms     average number of bedrooms per household
    - Population    block group population
    - AveOccup      average number of household members
    - Latitude      block group latitude
    - Longitude     block group longitude

:Missing Attribute Values: None
## IMPLEMENTATION DETAILS

DATASET: California housing DATASET

MODEL: Linear Regression

INPUT: 8 features

OUTPUT: House Price
## EVALUATION AND RESULTS

METRIC        VALUE

R2 SCORE      0.6

MSE           0.5
## KEY TAKEAWAYS

While doing this project i learnt the use of regression techniques using the sklearn library.
## How to Run

The code is built on Google Colab on an iPython Notebook. 

Simply download the repository, upload the notebook and dataset on colab, and hit play!
## Roadmap

What are the future modification you plan on making to this project?

- Try more models

- Wrapped Based Feature Selection
## Libraries

**Language:** Python

**Packages:** Sklearn, Matplotlib, Pandas, Seaborn
## Licence

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## Acknowledgements

All the links, blogs, videos, papers you referred to/took inspiration from for building this project. 

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

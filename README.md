## About the dataset

The following project uses [this](https://www.kaggle.com/datasets/crailtap/taxi-trajectory) dataset, taken from Kaggle.

It contains information about 1.710.589 different taxi trips from the city of Porto, Portugal between the 1st of July, 2013 and the 30th of June, 2014. 
Each trip is uniquely identified by an ID and includes data about the starting time of the trip, duration (indirectly measured), geographical coordinates of the path, along with a few other attributes.

## Scope of the project
 
The project is meant to showcase the cleaning, analysis and visual exploration process of the given dataset using Python 3.10.6 along with a few useful libraries such as Pandas, Numpy and Matplotlib.
 
 #### Data Cleaning
 
Since the data has not been previously cleaned or validated, it is first and foremost an exercise of data cleaning, which consisted of the following:
 * checking data types of each column
 * dealing with duplicate records
 * renaming variables to better reflect the meaning
 * adding relevant columns that would aid the subsequent analysis process from the information provided in the existing columns
 * marking invalid trip paths by identifying unrealistic distances traveled in short amounts of time

#### Analysis
The analysis was not tied to any specific end goal and thus it is mostly meant to explore the data through different metrics that are relevant for the full picture. Some of the questions what were answered are:
* What is the distribution of trip duration?
* What is the frequency of each type of call?
* What are the busiest days of the week?
* What are the busiest months of the year?
* Which stands are the most popular?

The project ends with a recommendation about the possible placement of new stands.

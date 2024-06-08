# Phase_1-DataAnalysis-Project
##**AVIATION IDUSTRY ACCIDENTS STUDY** 
## 1. Defining the Question
### a) Specifying the Data Analytic Question
> Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft.

> **Problem Statement:** You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor.

>You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.
### b) Defining the Metric for Success
Inorder to aid the company in venturing into the aviation industry,an analysis must be conducted on previous records to establish the **aircrafts to purchase** as well their **proneness to risks**.
### c) Understanding the context
The data provided is:The NTSB aviaton accident database that cointains information from 1902 and later about civil aviation accidents and selected incidents within The US,its territories and possessions, and in international waters.

[The dataset](hthttps://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopsestps://)
### d) Recording the Experimental Design
Throughout this notebook we will be exploring two csv files and taking them through the processes of Data Cleaning,wrangling,exploring and visualization.
### e) Data Relevance
The dataset is relevant for improving quality and safety of travelling by Airplane- through exploring accidents cases of different aircrafts and providing meaningful insights and recommendations.
#Importing Libraries
#Reading the Data
#Checking the Data
#Tidying the Dataset
From the bit of exploring above, it seems like the aviation data needs to be cleaned and sorted out for it to be used for further study and visualization.
#####From the observation above,we opted to replacing all null values in the dataset as their is a variation of the number of missing values in the columns and it is not advisable to drop the rows and or columns.

#Exploratory Analysis
###Distribution of Accidents in different Countries
![image](https://github.com/Sharon-Mukami/Phase_1-DataAnalysis-Project/assets/162372425/73792c6f-6dfb-4322-afe7-4d26e0460262)

###Distribution of Accidents in the U.S
![image](https://github.com/Sharon-Mukami/Phase_1-DataAnalysis-Project/assets/162372425/39d373d5-650a-4875-89af-4a0a45ce858b)

###The Top 10 Manufacturing('Make')Companies which are involved in accidents
![image](https://github.com/Sharon-Mukami/Phase_1-DataAnalysis-Project/assets/162372425/7fe20606-bcf6-4b10-bfc6-01c83833a41b)

#Conclusion
#####From our findings above, more accidents occurred in  the United States than anywhere else in the world.Most especially in the state of California-CA.:The CESSNA Manufacturing company has incurred the most accidents and is therefore the most risky one to invest in.

#Recommendations
####From the analysis done, the following recommendations can be given to the company:

#####1. If the company is interested to invest in the aviation industry in particularly The United States, it should carry out further thourough investigations on the causes of the accidents, the precautions taken over the years, investment,profit and loss rates.
#####2. The company should invest in travel overseas, since the accidents rate is not large.
#####3. Before making purchase on aircrafts, the company should analyse previous statistics on the manufacturing company inorder to avoid incurring losses and accidents.


#####A further study should be conducted on the costs incurred to get into the industry, government restrictions, demographic factors e.t.c inorder to ensure a successful launch into the industry.


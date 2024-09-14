# Google-Analytics-Case-Study
Preface:- This case is based on fictional bike-sharing company. The objective is to have more riders. Company differentiate customers as casual bikers who rides per hour or daily basis and annual subscription rider’s members. 
The company business model is profitable having more annual subscribed riders. So, the director of a company, Lily Moreno, Ask to have analysis based on more annual riders either which could new or converted from casual riders members towards annual members. 
So, marketing team needs to identify the insight of a data and as a data analyst you need to observe the riding inside patterns and come up with recommendations/suggestions for stake holders.
Company:- The company has roughly around 6000 riders members and having almost 700 stations locked into a network. The bikes can be unlocked from one station and returned to any other station in the system anytime. 
Mr. Moreno wants to have a new marketing strategy aim to convert casual riders into annual members. In order to do that, team needs to know how and why the casual riders will update to annual members? So, Moreno and their department are interested in analyzing the Cyclistic historical bike trip data to identify trends.

So in ASK phase the questions we need to be answered like;
What are the problems trying to resolve?
And How the data insights help to make business decisions?
So, the key is to identify the business task and come up with clear statements for key stake holder’s requirements. 
In the preparation phase, to analyze, the historical data can be downloaded from the https://divvy-tripdata.s3.amazonaws.com/index.html . I have downloaded Jan 2023-Dec 2023 zip files data to the local drive. I created a folder named Case Study Cyclistic and having 12 zip files. Each month is having separate dataset file. The files were than unzip in the same folder. Each file contains 13 columns. 
Each file contains one-month data, so we need to combine all data into one file for analysis of the data. After that we need to clean data, removing duplicates and not required data.
The combined data file is huge I use Big Query or R and Tableau for the processing. I used both R and Big Query since I learnt both these tools so I need to show that in my project too. First I use R for data binding of 12 files into 1 big file and write that on the local drive. I called that file in Big Query environment for further processing.

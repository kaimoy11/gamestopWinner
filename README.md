
—————————————————————————————————————————————————————
ReadMe
—————————————————————————————————————————————————————
Contents:
.ipynb- file containing program code
.csv -file containing stock price % change data set
ReadMe.txt

Introduction:
Welcome to the Reddit Social Media Scraper, this program has been built to withdraw and analyze reddit comments from the subreddit thread: r/wallstreetbets pertaining to: GAMESTOP, and find relation to historic stock activity.

Contributors:
Devon Johnson, Kai Moy, Tyson Mehrens, Zhenyu Zhen

Help:
If you need help or have questions about the program feel free to contact: johnsonde6@gmail.com, kaimoykai@gmail.com, tjmehrens@gmail.com, or zhenyuzhen0122@gmail.com 
 

Below are the instructions for how to run the program.


#################################################
## 																	##
##                         How to use Reddit Social Media Scraper				##
##																	##
#################################################

	1.	Requirements for Program 
	1.	Install Packages 
	1.	praw (Python Reddit API Wrapper) 
	1.	Learn more: https://praw.readthedocs.io/en/latest/  
	2.	vaderSentiment 
	1.	SentimentIntensityAnalyzer 
	2.	Learn more: https://praw.readthedocs.io/en/latest/  
	3.	Statsmodels 
	1.	Learn more: https://www.statsmodels.org/stable/index.html  
	2.	Import Classes 
	1.	csv 
	2.	os 
	3.	re 
	4.	numpy as np 
	5.	time 
	6.	datetime 
	7.	sklearn.linear_model 
	1.	LinearRegression 
	8.	statsmodels.api as sm 
	3.	Reddit User Account 
	1.	Login credentials 
	1.	Username 
	2.	Password 
	2.	Register for Reddit API 
	1.	client_id 
	2.	client_secret 

	2.	Launching the Program 
	1.	Connect to Reddit database  
	1.	praw client and login credentials 
	2.	Select subreddit 
	2.	Gather Data 
	1.	Query 
	2.	Store into lists 
	3.	Analyze Sentiment 
	1.	Vader compound scores 
	2.	Store in lists 
	4.	Count Sentiment Data  
	1.	Group sentiments by timestamp 
	2.	Store totals 
	3.	Calculate Averages 
	5.	List Ground Truth Data 
	6.	Run Linear Regression 
	1.	Set variables  
	1.	X₀=avg change in price 
	2.	X₁=pos_comment 
	3.	X₂= neg_comment 
	4.	X₃=daily_avg_pos 
	5.	X₄=daily_avg_neg 
	6.	Y = %change of stock price 
	2.	Numpy array 
	3.	Concatenate into one X 
	4.	Run Model 
	7.	Input Model Results into Stats Models API 
	1.	Display Stats Results 
	1.	R 
	2.	R² 
	3.	F-Statistic 
	4.	Std Err 

	8.	Evaluate 
	3.	Exit Program 
	1.	Close Jupyter Notebook 
	2.	Execute Terminal Window 
	
	
	
	![Screen Shot 2022-10-03 at 11 12 48 AM](https://user-images.githubusercontent.com/101154292/193648683-5217c84d-e2ab-447d-a229-b96671b01a23.png)

	
——————————————————————————————————————————————————————————————————————————————————————————————————————————

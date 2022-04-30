# K. Sreesh Reddy's Data Science Portfolio
This portfolio is a collection of notebooks that I prepared for experimenting with various Data Science and Machine Learning concepts along with the notebooks I submitted to competitions. Separate projects have their own category. 
## <u>Web Scraping:</u>
### Automated Scraping Project
Using BeautifulSoup and Selenium, we scrape data from websites and store them in a dataframe using Pandas. We use various websites such as CodeChef, StackOverflow and Flipkart.<br>
[Github Link](https://github.com/sreesh2411/Web-Scraping)

<hr>

## <u>Exploratory Data Analysis:</u>
### Stock Analysis
Stock Analysis is done on historic data so as to predict the trends which may occur in the future. Here we observe the stock prices of three companies, Tesla, Ford and GM in the 5 year range from 2012 to 2016. We also see if there is any relation between the three companies' stocks, view in the Moving Average (MA) form, observing the Daily Percentage Change and the Volatility, and Cumulative Return. Tools used are Pandas, Numpy, MatplotLib, Datareader, Scatter Matrix, Candlestick Chart, Box Plots.<br>
[Github Link](https://github.com/sreesh2411/Stock-Analysis)<br>
[NB Viewer](https://nbviewer.org/github/sreesh2411/stock-analysis/blob/master/StockAnalysis.ipynb)

### Statistically Best NBA Player
With the rise of sports analytics, the desire for efficiency and data-driven judgments in recruiting new players for NBA clubs is increasing. We can now look at an extensive list of granular stats that range from the box score statistic, which assesses a player's impact to the team, to basic metrics like offensive rebounds, rather than merely eyeballing a player and judging their surface level playing stats (points, shot attempts, etc.). We may evaluate players using these measurements and determine who would be a good fit for a certain club depending on their attributes. Main source of inspiration to pursue such a project was the movie MoneyBall.<br>
[Github Link](https://github.com/sreesh2411/NBA-Analysis)<br>
[NB Viewer](https://nbviewer.org/github/sreesh2411/NBA-Analysis/blob/main/nba_analysis.ipynb)

<hr>

## <u>SQL:</u>
### Car Rental System
Created a relational database wherein an admin exists whose responsibility is to update the registrations and update the rents and returns. In this rental a Customer who has been registered in the database can rent a car for any no. of days they want for a certain amount of fee. Cars are also registered in the database by the admin based on their make, model, and availability. Whenever a car has been rented by a customer, its availability status changes from “Yes” to “No” and a due date (date on which car will supposedly be returned) is provided. Customer details include name, address, customer id, phone no. and age. Some of the objectives were: 
- Identifying functional dependencies 
- Identifying keys of the relations based on FDs 
- Normalization
- Testing for lossless join property 
- Creating the tables including check constraints 
- Creating referential integrity constraints 
- Creating a trigger 
- Writing complex SQL retrieval queries.<br>
[Github Link](https://github.com/sreesh2411/DBMS-Project)

<hr>

## <u>Machine Learning:</u>
### Predict Medical Health Expenses
Project in which we try to predict the expenses due to medical health. Understood the importance of Data Analysis and Data Visualization for determining the association between features,
How to build intuition by building insights from Data Visualization,
How to deal with categorical variables,
Learnt about different Assumptions to be satisfied before using a Linear Regression Model, Learned different predictive models such as Linear Regression, Random Forest and Gradient Boosting model, Learned how to ensemble different models, Understood the importance of cross validation on the data, Learned the importance of comparing different predictive models.<br>
[Github Link](https://github.com/sreesh2411/ML-Projects/tree/main/Predict%20Medical%20Health%20Expenses)

<hr>

## <u>Natural Language Processing:</u>
### Auto Text Generation
Generation of Natural Language (NLG) It performs the function of a translator, converting digital data into natural language representation. Text planning, Sentence planning, and Text Realization are the essential components. Dataset: https://ocw.mit.edu/ans7870/6/6.006/s08/lecturenotes/files/t8.shakespeare.txt. The dataset was chosen from shakespeare lecturenotes with the following goal in mind: Our final goal is to generate the 51st text from a seed text of 50 words for a particular sentence. As a result, we were able to create models to generate the 51st text for a given sentence with 50 words as seed text. This can come in handy when we're writing a business or personal email or essay. Made use of Tensorflow, Keras and LSTM.<br>
[Github Link](https://github.com/sreesh2411/NLP-Projects/tree/main/auto-text-generation)<br>

### Twitter Sentiment Analysis
Sentiment Analysis of the tweet to computationally determine whether a piece of writing is positive, negative or neutral. Some novel steps I encountered in the project were understanding the working of textblob, understanding Twitter APIs and how to connect to them etc.<br>
[Github Link](https://github.com/sreesh2411/NLP-Projects/tree/main/twitter-sentiment-analysis)

For other NLP Projects, check out [this link](https://github.com/sreesh2411/NLP-Projects/)

<hr>

## <u>Deep Learning:</u>
To familiarize myself with various Deep Learning applications and algorithms, I implemented neural networks such as Convolutional Neural Netowrks (CNNs), Recurrent Neural Networks (RNNs), and Long Short Term Memory (LSTMs) on Topics such as Binary Data Classification, Breast Detection, IMDB Review Classification, and Multi-Class Image Classification.<br>
[Github Link](https://github.com/sreesh2411/Deep-Learning-Projects)

<hr>

## <u>Time Series Analysis:</u>
### Forecasting upcoming temperatures
This project deals with cleaning and analysis of data and drawing conclusions such as confirmations that the graph of temperatures are seasonal in nature etc. (EDA in notebook) and ARIMA is used to predict the future temperatures.<br>
[Github Link](https://github.com/sreesh2411/Time-Series-Analysis/tree/main/Predicting%20the%20temperatures)

### Predict future quantum of customers entering a shop
Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Forecasting is the use of a model to predict future values based on previously observed values. It is  widely used for non-stationary data, like economic, weather, stock price, and retail sales etc. In this project, we make use of time series models to forecast the future customers visiting the shop. Some major learnings were about types of decomposition, autocorrelation functions and conversion of data from non-stationary to stationary.<br>
[Github Link](https://github.com/sreesh2411/Time-Series-Analysis)<br>
[Link to ppt](https://github.com/sreesh2411/Time-Series-Analysis/blob/main/Time%20Series%20Forecasting-converted.pdf)

<hr>

## <u>Kaggle Competitions:</u> 
### Titanic - Machine Learning from Disaster
Link: https://www.kaggle.com/c/titanic/overview <br>
This is the legendary Titanic ML competition – the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works.

The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

Score:  0.80622 (Top 3%)<br>
[My Notebook](https://github.com/sreesh2411/Kaggle-Submissions/blob/main/Titanic/sreesh_titanic.ipynb)


### Housing Prices Competition for Kaggle Learn Users
Link: https://www.kaggle.com/c/home-data-for-ml-course <br>
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Score: 16268.60103 (Top 10%)<br>
[My Notebook](https://github.com/sreesh2411/Kaggle-Submissions/blob/main/Housing/sreesh_housing.ipynb)

<hr>





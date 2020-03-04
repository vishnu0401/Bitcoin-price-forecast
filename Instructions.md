The files with .ipyb extensions can be viewed with Jupyter notebook and spyder

Bitcoin.ipyb consist of codes used on inital stage of the project where steps like webscrapping and data cleaning had be done.

Bitcoin.csv file contain the initial uncleaned data scrapped from the site. 

The site from which the data is collected for the project is https://coinmarketcap.com/all/views/all/

Project bitcoin latest.ipyb contains the code which is used for EDA on cleaned data and it also contains different methods used to forecast the bitcon price, A span of one year price data is considerd for the analysis. The dataset used for this part is save as Bitcoin_Latest.csv file.

Initial rolling statistics method and Dickey Fuller test is done on the data to check whether the data is stationary or not.

To make the data stationary the closing price data had been converted using log functions till the data had been stationary.

The stationarity of the data can be observed from graphs and also consider the facts from the results of Dickey Fuller Test. 
ie, If the test statistics is below the critical values and also if the p value is < 0.05 we can reject the null hypothesis telling that the data had made stationary.

ACF and PACF tests also done to determine the values of p and q which s needed for ARIMA analysis. The values are obtained by plotting an graph.

Using the values of p and q the ARIMA analysis can be done and Root Mean Square Error had been calculated 

data set is then splitted into train and test datasets and using ARIMA analysis values had been predicted along with the error rate on each case.

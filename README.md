# Netflix-Movies-and-Tv-shows-with-Time-series
## Description:
Netflix find it hard to Know More about their target Audience and Measuring the changing Scale of Their preferences through the year so with using Time series analysis we can make netflix know more :)
## objective :
The goal of this project is to use time series models to get the best analysis we can get and provide netflix with more information 
## Requirements:
-numpy

-pandas

-matplotlib

-statsmodels.tsa.arima_model

## Approach:
-after loading the data and doing the preprocessing and cleaing step,I will do some visualization that will help me to know about Netflix audience as below I know now that netflix has over 50% of her audiance is adults and teens while the lowest rate of audiance that watch netflix is kids

![Alt text](https://github.com/menna566/Netflix-shows-analysis-with-Time-series/blob/main/netflix%20audiance.png)

and I also discovered what countries watch Netflix the most which was the United states as we see :

![Alt text]()

we also added the date and the month and the year columns to see the distribution of the shows that got added at those times :

![Alt text](https://github.com/menna566/Netflix-shows-analysis-with-Time-series/blob/main/countries.png)


## Results :
we applied tickey-Fuller test to provide us information about the stationarity of the data :

![Alt text](https://github.com/menna566/Netflix-shows-analysis-with-Time-series/blob/main/test_sta.png)



-Test Statistic: The test statistic is a measure of how strong the evidence is against the null hypothesis of non-stationarity,In this case the test statistic is -2.296104.


-p-value: The p-value indicates the probability of observing the test statistic given that the null hypothesis is true. In this case, the p-value is  0.173227 its high 

-So as higher p-value suggests weak evidence against the null hypothesis and also the test statistic (-0.771501) is greater than the critical values so This indicates that the time series is non-stationary, as it does not provide strong evidence against the null hypothesis of non-stationarity.

Here is the results after applying arima model :

![Alt text](https://github.com/menna566/Netflix-shows-analysis-with-Time-series/blob/main/ARIMA-Model%20.png)


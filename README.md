# Capstone-II--Yes-bank-stock-close-price-prediction-Supervised-ML-Regression-


**Problem Statement **-Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

**Business objective**:
Yes bank is private bank and it has many stake holders , so its matter that the stocks they own and price of their stocks . It’s very necessary to them to know the stock they own and price of the stock. So they could make decisions about the selling  or keeping then stock and know how much the business is get affected by the inflation of  the stock price.

**Inforamtion About the data:**
We have Yes Bank monthly stock price dataset. It has following 
features (Columns):
1)Open:  Opening price of the stock of particular month.
2)High: It is the highest price at which a stock traded during a period.
3)Low: It is the lowest price at which stock traded during a period.
4)Close: Closing price stock at the end of a Trading Day.
5)Date: We will use it as an index.

**conclusioon derived from the project:**

1] From the given data , which have less no po data points and few columns all the given features have linear relation between them.

2] We found data has no missing values and less no of outliers since data is small , we might have loss data.

3] We have seen that stock price was in continous rise upto 2018 and it went to its initial price after the news suddenly break  in india.

4] News afftected lot of market value of bank and loss of stock price in the market.

5] We want to predict the stock price of the yes bank , after applying lot of ML models we found that most of the model offer highest accuracy such as linear regression,lasso,ridge regression ,XGboost .

6] Amongst all the model we have applied , elastic net regression has the lowest accuracy .

7] From the above linear regression, lasso, ridge  we are able to predict the close stock price with the 99%  accuracy.

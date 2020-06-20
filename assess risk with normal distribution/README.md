# Evaluate Risk of Stock Return Using Normal Distribution¶
## Objective
We can model daily stock return using normal distribution. We have a large collection of data return from historic data. We can compute the parameter mean and and standard deviation in this collection. The interesting part is, if we transform log form, the distribution is not same as normal distribution, but it close enough.

Then, with calculate area under curve we can calculate the probability of losing or gaining in a certain percentage in one day. Using CDF (cummulative density function) of normal distribution we can calculate the risk.

Let X is random variabel for daily return of stock X. How many probability in single day stock X will lose more than 5%? then with CDF we simply find the value for P(X < -0.05) or 1 - P(X > -0.05)

## Case Study
If talk about risk, then we talk about loss on stock trading. Let say we as trader has loss tolerance around ~15% a years.

In this case we will evaluate that BBCA will drop 15% in next 1 years.

Stock Code: BBCA (IDX Market)

Data Period : Jan 1, 2019 - Dec 31, 2019

### Problem Statement:

1. Probability BBCA drop 5% in a single day
2. Probability BBCA gain 5% in a single day
3. How likely the stock price of BBCA were dropped over 15% in 1 year (has 220 trading days)

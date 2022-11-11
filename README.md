# Fintech540-Machine Learning For Fintech - Group_projet:smiling_imp:

## Description:
This is repo for a Machine learning Model-building project that takes cryptocurrency data as input and used some supervised(regression,classification) and unsupervised(density astimation, clustering) machine learning algorithms to find out some interesting patterns in the dataset.

## Architecture:
<img width="1000" alt="WeChat21a3a4952e0b415c9d0456e469408f09" src="https://user-images.githubusercontent.com/112578107/194975053-7ac343ea-93f5-4415-8840-c7309958070c.png">

Reggression (1 MODEL- liner regression: 2-3 people):
1. Fuction: As a benchmark to prove clusterings will be better.
2. Tasks:
   a. We need to have factors which bring influence on our cryptocurrencies' price. (S&P500, etc...)
   b. Choose three cryptocurrency to present
   c. Finish in one week

## Requirements
1.one model
2.focus on one kind of crypocurrency or `top 50/100 market cap`
3.Deadline of presentation: `11/17/2022`

## Motivation:
Machine learning in finance is now considered a key aspect of several financial services and applications, including managing assets, evaluating levels of risk, calculating credit scores, and even approving loans. Machine learning is a subset of data science that provides the ability to learn and improve from experience without being programmed.\
In this project, we will explore some possible ways that how unsupervised learnig algorithms(Clustering) could be applied on cryptocurrency and access their performance to find out whether there are some interesting discoveries.

## Take a peep into our dataset:
You can find out dataset here: web_link
For dataset, we have `1243590` entries and `12` columns:
> - `time_open` : 
> - `time_high` : Time cryptocurrency reachs highest price.
> - `time_low` :Time cryptocurrency reachs lowest price.
> - `quote.USD.open` : 
> - `quote.USD.high` : 
> - `quote.USD.low` : 
> - `quote.USD.close` :
> - `quote.USD.volume` : 
> - `quote.USD.market_cap` : The total market value of a cryptocurrency's circulating supply. It is analogous to the free-float capitalization in the stock market.
> - `quote.USD.timestamp` :
> - `symbol` : The symbol of cryptocurrency
> - `id` : With symbol, they are the unique id for cryptocurrency.

## Addtional Notes:
We might not try out all machine learning algorithms at the first stage. We might focus on unsupervised learning algorithm such as `clustering`.

## Overall Progress:
- [x] README file and some EDA work
- [x] Assign works
- [ ] Building models 
- [ ] Interpret the results
- [ ] Make PPT

## Problems we're facing

## Heyyy! Write your own progress here!👻
Patrick Duan: 
- K-means finished
![inertia_vs_k_plot](https://user-images.githubusercontent.com/112578107/200401361-a8a96a2c-679e-4e1c-b737-dcfce317a1a4.png)
- I did some EDA work and feature engineering on our data 
   - extract minute and sec as new features from time_high and time_low
   - drop other categorical columns
   - stanardize all numerical columns since distance matters in our model
- Remain to do:
   - result interpretation
   
## DEA FOR CLustering
Stacey Fang:

<img width="454" alt="Check_FinalType" src="https://user-images.githubusercontent.com/102479706/201259495-5848660b-e5cb-4e2e-adf7-b4bdf76caf77.png">
<img width="430" alt="CheckNull" src="https://user-images.githubusercontent.com/102479706/201259506-9a79bc5f-faca-459c-895d-eb384e4dda2b.png">

<img width="1008" alt="Description" src="https://user-images.githubusercontent.com/102479706/201259516-05a4aaa5-1004-4b54-badf-510676a895cb.png">
<img width="430" alt="All_Coin" src="https://user-images.githubusercontent.com/102479706/201259536-2fc31e51-12eb-41d6-9a50-16f3bbaf2ff5.png">

-DEA for whole dataset finished

Next Step:
1. Determine Coin we want to use 
2. Draw box-plot, Histogram, Kernel density, Q-Q plot, and etc

## Overall Progress:

# Introduction

There was a revenue decline in the Portuguese Bank, they would like to know why this decline
happened and what actions could be taken to mitigate the revenue decline. After preliminary
investigation, they believed that those clients who failed to pay for their credit card on time could
be a risk factor of the reduced revenue of the bank.
In the field of banking, the clients whose default value is Yes means that they do not pay their
credit card before the due time while the clients whose default value is No means that they
successfully pay their credit card before the due time. Therefore, if more clients can pay their
credit card on time, the poor status of bank operation may be improved.
However, one remaining problem for the bank is about how to distinguish these defaulters from
other clients based on other information that the bank can get from them. Hence, we will first
analyze data and find some underlying factors that are related to a high risk of default. Besides,
we will also apply machine learning skills to figure out a potential elegant model which can
better classify and predict potential defaulters based on their available information like their
social and economic status.
With this model system, the bank can better evaluate the conditions of clients and give a
customized credit card amount limit to different clients, so that the bank reduces the risk of
having clients with the default attribute and eventually increase the bank's benefit.

# Questions of Interest

## 1. Who will default (credit payment)?

This is the basic question we want to detect afterwards. As in our analytic step, we would
find out the basic characters of the customers who would default easily. In another word,
the risky customers.

## 2. Which socio-economic condition(s) foster defaulting?
The social and economic conditions are the most important factors which relate to
personal credit. We will mainly focus on them.

## 3. Which job roles had the maximum number of defaulters?

Jobs, as the main source for customers’ financial income, is the first factor we need to
analyse. The income level for the job, the average consumption level for the professional
group will lead directly to the final results.

## 4. Did the defaulter have any other pending loan (personal/housing/vehicle etc.)?

Pending loan, however, may be the cause of the default. Large sized loans mean the
financial burden of the customer is heavy. Once the capital chain breaks, default may
happen immediately.

## 5. The influence of marital status to the defaulter.

Behind the marital status, the stable family relationship and responsibility may cut down
the probability of default in common sense. We will analyse the relationship between
them.

## 6. The age related to the defaulter?
Same as the question before, age of customer may also be an important influence, as
people in different stages may contain totally different mindset and living habits.

# Dataset Description

Data Source: http://archive.ics.uci.edu/ml/datasets/Bank+Marketing
Dataset Name:  Bank Marketing Dataset
Dataset Domain: Business (Banking)
The data is related to direct marketing campaigns (phone calls) of a Portuguese banking
institution. It is a multivariate dataset with 45211 instances and 17 attributes, which gives a total

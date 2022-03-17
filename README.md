<div align="center">

# Project Title Goes here 

###  Add image/logo here
<img src='https://github.com/saumyagoyal95/Siemens-Hackathon/blob/2add5e4cb19d624e573a675cfbbd849332bd43a0/Title.png' width=500px> <br>
source : https://www.womenhackai.com <br>

  
[About](#about) •
[Configuration Requirements](#configuration-requirements) •
[Hypothesis and Findings](#installation) •

  
</div>

## 📒 About <a name="about"></a>

This repository contains the data analysis done during the Siemens hackathon(2021) - On Challenge#2 Campaign Performance Model
It was a 48hours event and we were suppose to come up with the key insights from provided data. We were suppose to find which variables have the highest impact on campaign performance? And which assets will yield the best results? 

Siemens wanted to support their campaign team in solving above mentioned pressing questions by developing a campaign performance model using numerical and categorical data and applying explorative and predictive analytics.

(Data not uploaded for the privacy reasons)

## 👨‍💻 Configuration Requirements <a name="configuration-requirements"></a>

What is the required configuration for running this code
1. Jupyter Notebook
2. Python Libraries used - numpy, panadas, matplotlib, seaborn

## 🖥️ Hypothesis and Findings <a name="installation"></a>

1. Which country should be the focus of future campaigns?
We know:
-	leads is most important 
-	leads/impression (LPI) is the best metric, when focused on lead generation with cost model → CPM = Costs per 1000 impression
-	leads/clicks (LPC)when CPC = Costs per click model is used

From the historical data, we think that the following countries are best to target:

<img src='https://github.com/saumyagoyal95/Siemens-Hackathon/blob/bf61a7c83d84765d0715d7b43aeb3d035c0c36e9/finding1.png' width=350px> <br>
In the BNL countries, the people are the most interested in the ads/topics.


2. What is the optimum number of advertisements per campaign with efficient cost per lead?

- upon feature engineering - found that 10-15 advertisements shows the best performance
<img src='https://github.com/saumyagoyal95/Siemens-Hackathon/blob/bf61a7c83d84765d0715d7b43aeb3d035c0c36e9/finding1.png' width=350px> <br>
In the BNL countries, the people are the most interested in the ads/topics.

3. Should the company pay for impression (CPM) or clicks (CPC)?

- Depending on the average cost per lead for getting clicks and impression it was evident from the data that getting clicks was more cost efficient in Italy and NDC region.

<img src='https://github.com/saumyagoyal95/Siemens-Hackathon/blob/bf61a7c83d84765d0715d7b43aeb3d035c0c36e9/finding1.png' width=350px> <br>


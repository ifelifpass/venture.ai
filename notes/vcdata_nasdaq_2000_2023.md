# Venture capital data distibution and Nasdaq correlation

Public databases of venture capital investments in startups are readily available in 2023. We can identify at least 53219 startup equity deals over the course of 2009-2022 with the amount of USD 1 M or more. However, as we examine these deals further, we see that they are not distributed uniformly. 

First, as time went on, more and more deals happened (until the market crash in 2022). This can be explained by more disclosure and/or more capital available. 
* If startups and startup investors no longer hide the investment terms and tell the public how much exactly the startup raised, we will get more deals recorded in databases (however, we cannot determine how many startup deals go unreported). 
* If more capital flows to the market, then more startups can raise more money, and again we will see to data either more deals, or larger deal size, or both. 

Second, VC dealflow metrics, aggregated either on monthly or on quarterly basis, correlate with changes in NASDAQ at a very high level. Among the reported startup deals we see a very solid connection with larger equity market. 

### Correlation between VC deal flow and Nasdaq Composite with a given period, 01.01.2009-01.01.2022
| VC dealflow metric | Monthly | Quarterly
| :--: | :--: | :--: |
| Count of deals | 0.813553 | 0.808097
| Sum of deals | 0.917514	| 0.939877
| Average deal size | 0.923845 | 0.969424
| Median deal size | 0.921061 | 0.950313



## VC deal count per month 2009-2023

```math
n = 53219
```
```math
R^2 = 0.81355295
```

![VC deal count per month 2000-2023](/img/count_deals_m_09_23.png?raw=true "VC deal count per month 2000-2023")

## VC deals sum per month 2009-2023

```math
\sum = \text{USD } 1,608,066,616,814
```
```math
R^2 = 0.91751398
```

![VC deals sum per month 2000-2023](/img/sum_deals_m_09_23.png?raw=true "VC deals sum per month 2009-2023")

## VC deals averages per month 2009-2023

```math
\bar{X} = \text{USD } 26,809,970
```
```math
R^2 = 0.923845459
```

![VC deals averages per month 2000-2023](/img/avg_deals_m_09_23.png?raw=true "VC deals averages per month 2009-2023")

## VC median deal per month 2009-2023

```math
\tilde{X} = \text{USD } 10,243,532
```
```math
R^2 = 0.921060585
```

![VC median deal per month 2009-2023](/img/med_deals_m_09_23.png?raw=true "VC median deal per month 2009-2023")


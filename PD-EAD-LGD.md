### Introduction

* In the credit risk modelling, one of the most crucial issues is the definition of a credit event which indicates that the loss has occurred. 
* Naturally, the credit event is the failure of payments, bankruptcy or default. 
* The practical question is, however, how todetermine that a loan which has not been repaid for some time period is indeed nonperforming, implying that the loss should be recognized by the bank. 
* For example, if the client is past due 10 days, this may already indicate that he or she has some troubles with repaying the loan, but it may be only a technical issue as well. 
* Hence, it is important to properly determine the threshold for the past due period. 
* In the credit risk management, the standard assumption is that a loan is considered to be defaulted (or non-performing) when the client is past due at least 90 days (3 months).

* When the bank has indications that a loan might not be fully repaid (e.g. dueto some past due payments), it should recognize the loss and create provisions (also called reserves or allowances). 
* In the accounting framework, this operation decreases the value of the loan (negative value on the side of asset) and creates costs (which imply a decrease in net profits and hence equity). 
* For this purpose, the bank estimates so called expected loss (EL). 
* The expected loss is based on the value of the loan (i.e. the exposure at default, EAD) multiplied by the probability, that the loan will default (i.e.probability of default, PD). 
* In addition, the bank takes into account that even when the default occurs, it might still get back some part of the loan (e.g. due to the bankruptcy procedure). 
* Hence, the previous figure is further multiplied by the estimation of the part of the loan which will be lost in case that a default occurs (i.e. loss given default, LGD). 


### Formula
* To sum up, the expected loss is calculated as follows:
`EL = PD × LGD × EAD OR EL = PD × (1 − RR) × EAD`,
where :

`PD = probability of default`

`LGD = loss given default`

`EAD = exposure at default`

`RR = recovery rate (RR = 1 − LGD).`

![image](https://user-images.githubusercontent.com/16324607/111039055-0c17c080-8452-11eb-83fe-857111374800.png)


* Expected loss is covered by revenues (interest rate, fees) and by loan loss provisions (based on the level of expected impairment).
* The expected loss corresponds to the mean value of the credit loss distribution.
* Hence, it is only an average value which can be easily exceeded. 
* Therefore, we define the unexpected loss as difference between a high quantile (i.e. 99 %) and the expected loss. 
* Banks should hold enough capital in order to fully cover the unexpected loss.

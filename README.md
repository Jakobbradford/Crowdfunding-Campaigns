# Crowdfunding-Campaigns

Business Question: What drives success (defined as whether campaign reaches their goal for money raised) in crowdfunding campaigns?

**Feature Selection**
| Feature  | Description |
|----------|----------|
|Whether the campaign promises a product|Many crowdfunding campaigns promise to provide products for investment|
|Goal amount|Dollar amount advertised for target investment amount|
|Technology product|Whether the campaign is for a tech product|
|Small business|Whether the campaign is for a small business|
|Fixed funding|Founders are only paid if the target goal is reached|
|IoT Device|Is the product an IoT device (e.g. Fitbit)|

**Model Selection**

Problem involves:
- Regression
- Prodicting a quantity
- 50<X<100,000 samples
- Few important features

Therefore chose the Lasso model

**Model Outcomes**

Best lasso permutation = [1,1000,1,0,0,1]
Fraction raised = 6.34

Pre Order Perk = Yes
Ideal Goal Amt. = $1000
Tech Campaign = Yes
Small Business Campaign = No
Fixed Fund = No
IoT Device = Yes

      

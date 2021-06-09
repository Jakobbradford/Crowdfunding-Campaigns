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

Scikit-learn documentation provides this useful diagram to determine what model fits a business problem.

![image](https://user-images.githubusercontent.com/83718882/121430412-114bb500-c946-11eb-931f-7a69bcb6e437.png)

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

**Conclusions**

Entrepreneurs

Businesses should place focus on highly technical products, especially those that can be sent to early investors. This incentivizes tentative donators by providing an exchange of value, which was demonstrated by the model. Additionally, avoid fixed fund campaigns, where campaigns only receive the funding if the goal is reached. There was a negative correlation between fixed funding and success, likely due to the fear that the donation won't go towards a product if it doesn't receive proper traction.

Regulators / Crowdfunding Sites

Given our lasso permutation, crowdfunding sites would have to respond accordingly to maximize investor trust. We believe that providing more rigid pre-launch guidelines to campaigns would be effective. This could include reviewing business plans and products more thoroughly on the site, minimizing dishonest advertizing used to generate larger donation volumes. Ensuring that campaigns follow-through on promises would be another useful step. The implications of this analysis are that campaigns can be tailored to amass larger funding for projects so long as this is done ethically.


      

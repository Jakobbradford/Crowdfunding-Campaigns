# Crowdfunding-Campaigns

Business Question: What drives success (defined as whether campaign reaches their goal for money raised) in crowdfunding campaigns?

**Feature Selection**
| Feature  | Description |
|----------|----------|
|Whether the campaign promises a product|Many crowdfunding campaigns promise to provide products for investment|
|Goal amount|Dollar amount advertised for target investment amount|






Conclusion

Better results were expected from the Logit regression due to its powerful capability to solve binary classification problems. Perhaps we could have done a better job tuning the prameters of the model or selecting different features. Despite the overall accuracy score, we were surprised by the precision and recall statistics.

                     Predicted Group 0  	  Predicted Group 1
Actual group 0              4484                	185
Actual group 1              1054                	264
                  Precision   	  Recall     F1-score
          0         0.810     	   0.960     	0.879
          1         0.588     	   0.200     	0.299
   Accuracy         0.793
While the model is useful for predicting non-defaults correctly, it falters in predicting defaults. Future work of this project could involve removing demographic variables that aren't viable for analysis. Additionally, comparing multiple models such as XG boost and random forest and using the model with the highest overall AUC would benefit the analysis. This model potentially has effective real world implications for banks, which would reduce loan default losses and predict default behaviors of their customers.

# AB Test Project Example

For this project, we will be working to understand the results of an A/B test
run by an e-commerce website. Our goal is to help the company understand if 
they should implement the new page, keep the old page, or perhaps run the 
experiment longer to make their decision.

## Dataset

The data consists of information regarding 294478 user of an e-commerce 
websitebike with 5 features that held various informations about each user,
including user_id, timestamp, group, landing_page and whether the user have
converted to the new page or not.


## Summary of Findings

Looking at the p_values from the statistics summary, we can say that we don't
have a strong relationships between each of explanatory variables, interactions
and the response variable, then it is statistically insignificant to say that 
these expalanatory variables or interactions we just added are good predictors
for 'converted' response.

Also, by lookig at the exponential of each coefficients, there is no a significant
change in the odds after we added the interaction between country and the ab_page.
So, in summary, we can conclude that the new pages doesn't really leads to greater
conversion rate and we can stay under the null hypothesis.


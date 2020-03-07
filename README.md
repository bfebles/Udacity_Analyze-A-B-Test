# Udacity_Analyze-A-B-Test

The goal of this project is to understand the results of an A/B test run by an e-commerce website.The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product.I worked through jupyter notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

Required Tools
* Python(Pandas, Numpy, Matplotlib, StatsModels, Scipy)

Part I - Probability 
Probability was calculated to understand the conversion rate of control and treatment group.

Part II - A/B Test
Hypothesis test was run with an assumption of old page being better than the new one. Sampling distribution was performed on random 10,000 data points and P values were calculated for both old and new page.

Part III - Regression
Logistic regression was performed as a difeerent approach to see the results in the A/B test. Regression model was instantiated uisng statsmodels to perform null and alternate hypothesis. In addition, an effect was added based on different countries user to determine its impact on the conversion rate.
      

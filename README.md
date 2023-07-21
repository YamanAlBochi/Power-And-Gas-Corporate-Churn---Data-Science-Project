# Power-And-Gas-Corporate-Churn---Data-Science-Project
A major gas and electricity utility that supplies to corporate, SME (Small &amp; Medium Enterprise), and residential customers. The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with us to help diagnose the source of churning SME customers..........





# Task 1 - Business Understading and Hypothesis Framing: 

- In order to test the hypothesis of whether churn is driven by the customers’ price sensitivity, we
would need to model churn probabilities of customers, and derive the effect of prices on churn
rates. We would need the following data to be able to build the models.

- The Data needed:

1. Customer data - which should include characteristics of each client, for example,
industry, historical electricity consumption, date joined as customer etc.
2. Churn data - which should indicate if customer has churned.
3. Historical price data – which should indicate the prices the client charges to each
customer for both electricity and gas at granular time intervals.

- Once we have the data, the work plan would be:

1. We would need to define what price sensitivity is and calculate it.
2. We would need to engineer features based on the data that we obtain, and build a
binary classification model (e.g. Logistic Regression, Random Forest, Gradient Boosted
Machines to name a few).
3. The best model would be picked based on the tradeoff between the complexity, the
explainability, and the accuracy of the models.
4. We would subsequently dive deeper into why and how price changes impact churn.
5. Last but not least, the model would allow us to size the business impact of the client’s
proposed discounting strategy.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Task 2 - Exploratory Data Analysis:

- I Perform some exploratory data analysis. Check into the data types, data statistics, specific parameters, and variable distributions. This first step is for us to gain a holistic understanding of the dataset.


- We Verify the hypothesis of price sensitivity being to some extent correlated with churn. It is up to us to define price sensitivity and calculate it.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Task 3 - Feature Engineering and Modelling: 

- Our team now has a good understanding of the data and feels confident to use the data to further understand the business problem. The team now needs to brainstorm and build out features to uncover signals in the data that could inform the churn model. Feature engineering, is one of the keys to unlocking predictive insight through mathematical modeling. Based on the data that is available and was cleaned, we'll identify what we think could be drivers of churn for our client and build those features to later use in your model.

- First we'll focus on building on top of the feature that your colleague has already investigated: “the difference between off-peak prices in December and January the preceding year”. Once we have a set of features, we'll train a Random Forest classifier to predict customer churn and evaluate the performance of the model with suitable evaluation metrics.

- Recall that the hypotheses under consideration is that churn is driven by the customers’ price sensitivities and that it would be possible to predict customers likely to churn using a predictive model. If we’re eager to go the extra mile for the client, when you have a trained predictive model, remember to investigate the client’s proposed discounting strategy, with the head of the SME division suggesting that offering customers at high propensity to churn a 20% discount might be effective. Building our models and test them while keeping in mind you would need data to prove/disprove the hypotheses, as well as to test the effect of a 20% discount on customers at high propensity to churn

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

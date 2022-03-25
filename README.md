# Optimal offering strategy for large producers based on market price response learning

This repository hosts a practical example for the case study in the paper "Optimal offering strategy for large producers based on market price response learning".

(Link for paper access is coming soon)

File descriptions:
- "dataset_price_learning.csv" is the main dataset. Variables regarding GENCO block prices and quantities, demand, renewable forecasts, different lags, etc. are included.
- "coef_distribution.csv" contains the posterior coefficient distribution fitted to each variable by means of bayesian linear regression.
- "dif_matching_offers.csv" brings the difference between the matching energy and the sales offers in the two months prior to June '19 (the month use for testing in the case study). This difference is needed for the marginal price computation approximation in the out-of-sample validation process.
- "market_blocks.csv" contains the discretized blocks for the GENCO's competitors. They will be employed in the out-of-sample validation to simulate the market functioning.
- "opti_model.ipynb" is the main notebook where the stochastic optimization model and the out-of-sample validation is presented. In the uploaded notebook, price flexibility is fixed to 10% and the risk aversion level is null. 

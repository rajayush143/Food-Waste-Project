# Science Fair Project - 2021

Experts estimate supermarkets are responsible for 10% of U.S. food waste, accounting for 43 billion pounds of waste and $18.2 billion in lost value annually. When food waste goes to landfills and rots, it produces methane, a greenhouse gas that is 84 times more potent than carbon dioxide. The Retail Food Waste Action Guide recommends enhanced demand forecasting as the primary mechanism to reduce food waste.

To help grocery stores predict demand for perishables, we developed software that predicts perishable item sales multiple days into the future. We used an Ecuadorian grocery chain’s sales data and built multiple models, including a regularized autoregressive model, a heterogeneous ensemble model, and a gradient boosted decision tree. 

These models were evaluated using MAPE (mean absolute percentage error) and RMSLE (root mean squared logarithmic error). On the test set, we achieved a MAPE of 18.9% when forecasting seven days into the future for the highest selling perishable item. Additionally, we were able to forecast sales of the 90 highest-selling items seven days into the future with an average error of 35%. More generally, we improved on status quo forecasting techniques by 10-15%. This software has the potential to reduce food waste in the US by up to 5 billion pounds per year.

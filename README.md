Churn prediction in the utility industry
The client is PowerCo - a major gas and electricity utility that supplies to small and medium sized enterprises.

The energy market has had a lot of change in recent years and there are more options than ever for customers to choose from.

PowerCo are concerned about their customers leaving for better offers from other energy providers. When a customer leaves to use another energy service provider, this is called churn.

This is becoming a big issue for PowerCo and they need help to diagnose the reason why their customers are churning.

During the meeting, we discussed some potential reasons for this churn, one being how "sensitive" the price is. In other words, how much is price a factor in a customer's choice to stay with or leave PowerCo?

To test out the hypothesis of whether churn is driven by the customers' price sensitivity, we would need to model churn probabilities of customers, and derive the effect of prices on churn rates.

We acquired the following data from PowerCo to be able to test the hypothesis.

Customer data - which should include characteristics of each client, for example, industry, historical electricity consumption, date joined as customer etc.
Churn data - which should indicate if customer has churned
Historical price data - which should indicate the prices the client charges to each customer for both electricity and gas at granular time intervals.
The work plan would be:

We need to define what price sensitivity is and calculate it
We need to explore to gain a solid understanding of the data
We need to prepare the data and engineer features for modeling
Then, we can test our hypothesis using a binary classification model (e.g. Logistic Regression, Random Forest, Gradient Boosted Machines to name a few)
We would choose a model from one of the tested algorithms based on the model complexity, the explainability, and the accuracy of the models.
With the trained model, we would be able to extrapolate the extent to which price sensitivity influences churn.

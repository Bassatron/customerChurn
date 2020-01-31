# Predicting Customer Churn

## Description
This repository and work in the notebook were inspired by the Amazon Machine Learning Predicting Customer Churn article presented at AWS re:Invent 2016, and can be found here: https://aws.amazon.com/blogs/machine-learning/predicting-customer-churn-with-amazon-machine-learning/. I set out to not only replicate the article's process of reducing customer churn costs by using machine learning, but to see if I could improve upon their results through better modeling, and thus greater cost savings.

The goal of this work was to see how we could apply machine learning to customer churn to reduce the overall average cost of a customer leaving. The data comes from a phone company, where the phone numbers have been anonymized.

## Results

By using machine learning, I was able to significantly reduce the costs associated with customer churn. Without using my models we had an average customer churn cost of $72.46, and I was able to bring that down by $36.48 to a total cost of $35.98. That represents a ~50% decrease in customer churn costs, and for an operator with 100,000 customers that means over $3.5MM in savings.

![Cost by Model](https://github.com/Bassatron/customerchurn/blob/master/figures/costs_by_model.png?raw=true)

Using my knowledge of various machine learning techniques, I was able to improve upon the original papers cost savings of $22.15 and increase the savings all the way to $36.48. That's ~60% in extra cost savings and $1.5MM in extra cash given 100,000 customers! This exercise has reinforced that data science isn't just building the best models possible, but taking the insights derived from those models and data, and applying them impact the core business.

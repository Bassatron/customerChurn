# Predicting Customer Churn

## Description
This repository and work in the notebook were inspired by the Amazon Machine Learning Predicting Customer Churn article presented at AWS re:Invent 2016, and can be found here: https://aws.amazon.com/blogs/machine-learning/predicting-customer-churn-with-amazon-machine-learning/. I set out to not only replicate the article's process of reducing customer churn costs by using machine learning, but to see if I could improve upon their results through better modeling, and thus greater cost savings.

The goal of this work was to see how we could apply machine learning to customer churn to reduce the overall average cost of a customer leaving. The data comes from a phone company, where the phone numbers have been anonymized.

## Results

By using machine learning, I was able to significantly reduce the costs associated with customer churn. Without using my models we had an average customer churn cost of $72.46 per customer, and I was able to bring that down by $49.56 to a total cost of $22.90 per customer That represents a 68.4% decrease in customer churn costs, and for an operator with 100,000 customers that means nearly $5MM in savings.

My results were a significant improvement over those from the initial article, where their model only lowered costs to $50.30, which entailed a cost savings of $2MM.

Through this exercise, I learned that single domain knowledge is not enough to realize the benefits of data science. It's important to know what mechanics we can use to better optimize our models, and realize the full benefits of machine learning. I also learned how to take the results of a model, and using those to make impacts on the business, and drive decision making.

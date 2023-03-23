# Real-estate-in-Bangalore
### Classification and Prediction problem


**Data** 

The data consists of features of real estate in different areas of Bangalore. It was pre-processed for convenience. The original data can be found here. 

Variables:

• availability: is the property available immediately (1) or in the near future (0). 
• total_sqft: the area of the property in square feet (1 foot = 30.54 cm). 
• bedrooms: the number of bedrooms in the property. 
• bath: the number of bathrooms in the property. 
• balcony: the number of balconies in the property. 
• rank: the ranking of the neighborhood in terms of average price (1 is the highest). 
• area_type: is the property type a built up area (B) or plot area (P). 
• price in rupees: the price of the property.  

Split:

• Train: rows 1-8040.  
• Validation: rows 8041-10050. 
• Test: rows 10051-12563.  

**Section A **

1. Decision Tree: Implement a Decision Tree (classifier and regressor) algorithm in Python. 
2. AdaBoost: Implement an AdaBoost (classifier) algorithm in Python. Machine Learning 2022  

**Section B **

1. Classification: Use both models from section A and predict the area type (B, P), using all the features in the dataset. 
2. 2. Regression: Use the decision tree model from section A and predict the price of a property, using all the features in the dataset.  

**Section C**

1. Sklearn Models: Implement the models (including hyperparameter tuning) from section B using built-in function from Sklearn. 
2. 2. Comparison: Compare the result of your program and the built-in Sklearn models in terms of metrics and runtime. If there are differences, suggest an explanation.  

**Section D**

1. Gradient Boost Regressor:  
  • Implement a Gradient Boost Regressor algorithm in Python. 
  • Run the gradient boost algorithm on the given data to predict the price of a property. 
  • Compare the algorithm’s performance to the built-in Sklearn model and the previous models that you implemented. 
2. Classification Metrics:  
  • Report the sensitivity and specificity metrics of section B(1). 
  • Is there a significant difference between the scores? Suggest an explanation to why that may be the case. 
  • Suggest and apply a method to improve the scores. 
3. Performance:  
  • Additional bonus points (up to 5) will be given for  outperforming other students (in terms of metrics). Make sure to provide an explanation. 

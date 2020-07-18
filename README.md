# Mobility Analytics (Dataset from JanataHack)
Mobility plays a dynamic role in connecting people and crucial for many businesses.
Passengers want to move from A to B as comfortable as possible. The quality of service as well as operational efficiency can have a huge impact on gaining customer satisfaction. The analysis of mobility data can provide meaningful insights and help solve the challenges.

Mobility Analytics is being used by many ride-sharing companies like Uber, lyft to improve passenger's riding experience and make it efficient by means of digital technologies. 

## Steps:
1. Data Preparation and analysis: 
   Understanding data, handling missing values, applying logarithmic transformation
   Relationship between factors has been visualized.
   
2. Model building and comparison:
   Different Machine learning algorithms have been built and accuracy score has been checked

3. Prediction: 
   The model, built on train dataset, when used on test data showed that the model has predicted the higher number of              Pricing_Type_2.0 category, followed by Pricing_Type_3.0 and then by Pricing_Type_1.0 categories. This prediction on test        dataset shows similar pattern observed in train dataset. This confirms the good prediction capability of built XGBoost          model.

4. Check accuracy of prediction:
   XGBoost model has Accuracy Score 71 %, which is better than
   Logistic Regression Accuracy Score 69 %

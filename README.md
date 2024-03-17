# Data Scientist Professional Practical Exam Submission

## Introduction

### About Tasty Bytes
Tasty Bytes was founded in 2020 in the midst of the Covid Pandemic. 
The world wanted inspiration so we decided to provide it. We started life as a search engine 
for recipes, helping people to find ways to use up the limited supplies they had at home. 
Now, over two years on, we are a fully fledged business. For a monthly subscription we will 
put together a full meal plan to ensure you and your family are getting a healthy, balanced 
diet whatever your budget. Subscribe to our premium plan and we will also deliver the 
ingredients to your door.

### Customer Request
Hi, We haven’t met before but I am responsible for choosing which recipes to display on the 
homepage each day. I have heard about what the data science team is capable of and I was 
wondering if you can help me choose which recipes we should display on the home page?

At the moment, I choose my favorite recipe from a selection and display that on the home page. 
We have noticed that traffic to the rest of the website goes up by as much as 40% if I pick a 
popular recipe. But I don’t know how to decide if a recipe will be popular. More traffic means 
more subscriptions so this is really important to the company.

Can your team:

- Predict which recipes will lead to high traffic?
- Correctly predict high traffic recipes 80% of the time?

We need to make a decision on this soon, so I need you to present your results to me by the end of the month. 
Whatever your results, what do you recommend we do next? Look forward to seeing your presentation.

### Results
The prediction of the expected traffic has been successful with the highest accuracy score of 81%, 
exceeding the customer request by 1%.

The optimum model for the prediction is Logistic Regression having tried multiple different models such as;

- Random Forest Classifier
- XGBoost Classifier
- Linear Discriminant Analysis


Following fine tuning, the best model was a Logistic Regression model

Fine Tuned Logistic Regression

          precision    recall  f1-score   support

       0       0.74      0.70      0.72        69
       1       0.84      0.87      0.85       129

#### Accuracy = 0.81 = 81%

This model shows good precision, recall and therefore f1 score on the target class, meaning, 
that if a recipe is truly a high traffic item, this model is likely to be accurate.

This in combination with the overall accuracy of 81% indicates that this model will be 
satisfactory to the customer.



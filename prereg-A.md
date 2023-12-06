# Form A for preregistering predictive models: Problem Definition
**Do not** edit or remove the questions. Add your answers below each question. 

Answers can be updated by updating this file and checking in to git. 

## A.1: Research question
**Q. What problem are you studying?**
*Example answer: Predicting who will survive the Titanic disaster.*

Answer: 

## A.2 Dependent variable
**Q. What is the main outcome of interest and how is it measured?**
*Example answer: Binary label (survived or deceased) in ground truth data.*

Answer:

## A.3 Independent variable
**Q. What features will you use to predict this outcome?**
*Example answer: I'll use all the features available in my dataset (11 features). I will perform feature engineering using recursive feature elimination (feature_selection.RFE in scikit.learn).*

Answer:

## A.4 Training data
**Q. How was the training data constructed?**
*Example Answer: Historical information about passengers on the ship. I will split this data to reserve a validate set equal in size to the test set.*

Answer:

## A.5 Test data
**Q. How will the test dataset be constructed? Will new data be collected, or will the test set be synthetically constructed?**
*Example answer: Randomly set aside 20% of observations for test set.*

Answer:

## A.6 Data transformations
**Q. Will you filter or transform the data from its raw form in any way?**
*Example answer: I'll remove the cases with missing values in any of the variables.*

Answer:

## A.7 Metrics
**Q. How will you measure the success of your model in predicting the outcome? If you are using a measure such as accuracy that requires thresholding of a continuous prediction, please specify the threshold(s) you will use.**
*Example answer:Precision in the top 100 most highly predicted cases (classification, unthresholded) OR AUC (classification), precision w/ threshold of 50% (classification).*

Answer:

## A.8 Baselines
**Q. Will you compare your method to other baselines? If so, which ones?**
*Example answer: Logistic regression with the same features*

Answer: 

## A.9 Anything else
**Is there anything else you would like to pre-register before training and validation?**
*Example answer: No*

Answer:



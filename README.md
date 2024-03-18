# Credit-risk-classification

   In this assignment, a model was trained on data pertaining to healthy and high-risk loans.  Factors such as interest rate, borrower income, total debt, debt to income ratio, derogatory marks, and loan size were taken into consideration and incorporated. Ultimately, the goal was to create a model that would be able to successfully and consistently assess the creditworthiness of potential borrowers. Based on these considerations, the model would try to predict whether a loan taken by a borrower would be more likely to be paid successfully (0) or defaulted (1).

   After creating the label (loan_status) and feature sets, the data was split into training and test datasets (75% to 25% respectively). Next, a logistic regression model was created and fit using the training data. Once completed, the model was ready to make predictions on the test dataset. A confusion matrix and classification report on the test data were printed to evaluate the reliability of the model. The results of this evaluation are as follows:

   •The model boasts 100% precision and recall for healthy loans, indicating that it correctly guessed an extremely high percentage of healthy loans. 
    
   •With a 100% in the F1 score for healthy loans, it reflects that the model is healthy and not being “cheated” or biased in some way.
    
   •For high-risk loans, the model’s precision was 87%, indicating that some healthy loans were incorrectly classified as high-risk loans (False Positives).
    
   •For high-risk loans, the model’s recall was 89%, indicating that some high-risk loans were incorrectly classified as healthy loans (False Negatives).
    
   •Once again, the F1 score indicates a healthy and unbiased model.
    
   •In the confusion matrix, we see that out of 18,759 applications, there were only 67 false negatives and 80 false positives.
    
   •The accuracy of the model is 99%, with correctly guessed healthy loans contributing immensely to this metric. 

   In conclusion, this logarithmic model is extremely adept at correctly predicting healthy loans while slightly less successful at predicting high-risk loans. The marginally higher recall for high-risk loans suggests that the model is better at avoiding false negatives than it is at avoiding false positives regarding high-risk applications. If given the choice, it is likely that credit lenders would prefer the model to more accurately identify high-risk loans, even if that came at expense of healthy loans being incorrectly classified. All in all, this model is relatively robust. With more data or a few adjustments, I am confident that it may get even better at predicting high-risk loans. For that reason, I would recommend that the company adjusts and utilizes this model. 



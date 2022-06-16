# Machine-Learning

Classification: 
Model that you can predict the results which are categorical, for example, the prediction of spam emails( 1 means that it is spam email, 0 means not), etc. In terms of how good the model is, we try to use confusion matrix to get the evaluation of our model. But when it comes to the evaluation, we have to consider the accuracy, precision, recall, F1 in order to meet different situation.


Accuracy (it does not apply to the situation like, prediction of disease)


     TP + TN
     
= ----------------          

      Total
   
Precision (calculate the true positive rate out of all predicted postives)：it is a good measure when the cost of the false positive is high. 

       TP
       
= ----------------                        FP: spam email (P) non-spam email(N) --> mis-classified non-spam email to spam, which results in missing important emails

     TP + FP
     
Recall (calculate the true positive rate out of all actutual positives)

       TP
       
= ----------------                        FN: fraudulent cases(P) non-fraudulent cases(N) --> misclassified fraudulent transaction to non-fraud

     TP + FN
     

F-1 Score:

       Precision * Recall
       
= 2 * ----------------------

       Precision + Recall

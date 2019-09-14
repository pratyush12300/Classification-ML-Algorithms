   This is a bank data which had a lot of variables in categorical format .Since any model in sklearn needs numerical value ,we will use replace function for variables with 2 levels and getDummies for levels more than two.The requirement is to develop a statistical model which predicts whether a customer will subscribe to the term deposit or not ?.The model should also be efficient in targeting and less bothering to uninterested customers as the bank has faced complaints regarding irrelevant product calls.We also need to devise a framework to choose which customer to call and which one to leave alone .Since the data is binomial (yes/no).We will be making a classification.We will start with Logistic Regression .

Data Exploration and Use Case Story Line

   The model has been deployed and parameters to check how good the model is explained in the code.Coming back to the original requirements where the model should be efficient in targeting and less bothering to uninterested customers
 

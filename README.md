# ML-Project-Spam-mail-prediction
As cleaning and preprocessing of the dataset is done,
we can use "train_test_split" function to divide the dataset
into training and testing data. To implement the training data
on the model and predict whether the text is spam or not, we
need to import Logistic Regression algorithm from the
"scikit-learn" library and performance metrics. In our
project, we have used the Logistic Regression algorithm for
classification purpose. Logistic Regression is an excellent
predictive modeling algorithm that models probabilities for
classification problems with two or more possible outcomes.
Logistic Regression is similar to Linear Regression, where
we get an S-shaped line to get output in either 0’s or 1's
instead of a straight line. To get this S shape curve, Logistic
Regression uses the sigmoid function. The sigmoid function
gives probabilities between 0 and 1. In our model, logistic
Regression will give us whether the message is spam or not.
Where if it’s 0, it would be spam else it would be ham if the
value is 1.

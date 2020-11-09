# machine-learning

## Linear Regression

## Why Linear model makes sense ? 

If a simpler model works then why don't we use it.The other reason why we choose linear model is that, linear model rarely overfits. 

## What is overfitting ?

If a model is overfitting, then it performs very well for the training data set prediction. But when it comes to test data or actual use case then it fails to predict a good value. 

## What do we choose squared error loss (mean squared error)  method , could we not have used just the absolute value ?

The absolute value is not convenient, because it doesn’t have a continuous derivative, which makes the function not smooth. Functions that are not smooth
create unnecessary difficulties when employing linear algebra to find closed form solutions
to optimization problems. Intuitively, squared penalties are also advantageous because they exaggerate the difference between the true target and the predicted one according to the value of this difference. We might also use the powers 3 or 4, but their derivatives are more complicated to work with
 TODO: what he meant by this ? 

## Why we call it Logistic regression , while its actually a classification problem ?

The name comes from statistics and is due to the fact that the mathematical formulation of logistic regression is similar to that of linear regression.

## Why can't we use the y=mx+b linear equation in logistic regression ? 

The problem with just the linear equation is the the y is a real number, and when we are dealing with the classification problem we need two values ( binary classification). And the y=mx+b alone will not be enough. We need to somehow convert the y value to be between two values.

## What is standard logistic function or Sigmoid function ? 

Even though we use a linear equation to solve a classification problem , the values of he linear equation can be any Real Number, but our classification ( binary classification ) needs just two values. We can use another function which can take the value of y and map it to either 0 or 1.

## What is maximum likelihood ? 

The optimization criterion in logistic regression is called maximum likelihood. Instead of minimizing the average loss, like in linear regression, we now maximize the likelihood of the training data according to our model.

## What is a decision tree  ? 

A decision tree is an acyclic graph. An alrogithm used to train for classification problem ? 

## What is model and training. 

The process of building a model is called training. A model is a statistical ,....

## What is parametric vs non-parametric learning algorithms ? 

## Why  linear regression has a closed form solution ? , What exactly does it mean ? 


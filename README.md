# DSCI 521 Q6.0.1
[link of my repo from mybinder](https://hub.mybinder.org/user/mikeymice-blog_lab2-1-jxmzctdw/tree)





### What is Cross Validation?

We all have heard about `prediction` when it comes to Data Science. We know that prediction can be measured in terms of accuracy (the percentage/fraction of examples that we predict correctly from our test/unseen dataset). Ever wondered what's the process which data scientists follow to obtain such good predictions (they definitely don't obtain it in the first try!)? So, let's talk about the concept of `Cross Validation` and see how it helps us to improve our predictions.

Let's consider how we are learning Python programming in a course. We first start with the basics and learn about the basic commands in Python. With time, we learn how to write for/while loops and if/else conditions. Now, to test our knowledge and what we have learnt so far, we solve questions in lab assignments. The score that we get will tell us how good we are with Python and its syntax. Now, before the second assignment, we learn some more Python including where we went wrong in the previous one. And this process continues as we learn new things and apply them to unseen Python programming problems. If the assignment asks a kind of a question which we have never seen before, then we will have a hard time solving that one. Otherwise , we will be able to provide a decent solution to the problem.

This is quite similar to how data scientists improve their predictions using `Cross Validation`. In cross validation, we keep aside a part of the training dataset as the validation dataset (note that we already know the output variable values in this set). This set will be similar to the lab assignments in our previous example. The remaining training dataset is analogous to what we learnt in class in the Python course. A machine learning model is trained on the remaining dataset and then predictions are made on the validation dataset. We can now calculate our accuracy on the validation dataset by comparing the model output to the actual values we already have for the set. This helps us gauge the efficiency of our current model (just like our lab score tells us about our understanding of the course).

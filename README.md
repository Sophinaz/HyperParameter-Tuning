<h1>Report</h1>

Overall process:

I wanted to use two different models, one regression based and one tree-based like suggested. 

For that I used SGD regressor and Gradient Boosting Regressor respectively

I wanted to change one of the hypertuning algorithms, so that it wouldnt be the same as the lecture. 

For that, I used Bayes search. I used it because it was suggested, from the resources I used, that it is better than grid search in that it doesn't bruteforcely try everything but it tries to be probablistic about it.

But the problem with my approach was with the choice of the models. 

I have finally found out that the GBR is better than SGD in datasets that are complex and non-linear. For that reason in my case, the Gradient Boosting has had a better perfomance than the SGD regressor.

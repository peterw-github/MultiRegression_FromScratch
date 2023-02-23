# Multivariable Linear Regression, From Scratch

<br>

Hello!

The purpose of this project, was to get a solid understanding of a simple machine learning model, and multivariable linear regression.

So, to accomplish this, I first went through all of the underlying mathematics. 

Then, I created a completely made up, linear relationship between a bunch of independent variables (twelve as an example, x0, x1, ..., x11, but this can be changed in the code), and a dependent variable (y). The coefficients, the constant at the end (k), and the independent variable data (the instances), were all randomly generated. 

I then created a machine learning model, with randomly generated weights (w0, w1, ..., w11), and a bias (b). 

From there, I trained the model using the randomly generated data, and compared the model after it's been trained, to the made up model. Unfortunately, not all weights/ matched up with the corresponding coefficients, nor the bias and constant, so the prediction model didn't perfectly emulate the actual made up model, but it was reasonably accurate.

Overall, while the prediction model didn't come out perfect, the overall process of creating it, and rigorously going through the underlying mathematics, certainly did significantly improve my understanding of the core principles of machine learning in simple cases, and multivariable linear regression.


<br>
<br>
<br>

## Walkthrough of underlying mathematics:
An explanation of the underlying mathematics is here: <br>
https://github.com/peterw-github/MultiRegression_FromScratch/blob/main/Explanation/Math%20Explanation.pdf


<br>
<br>
<br>

## Optional:
To find a good learning rate/alpha value, I simply used the trial and error method (trying a value, then decreasing by an order of magnitude and trying again, over and over until divergence DOES NOT occur). The details/code can be found here: <br>
https://github.com/peterw-github/MultiRegression_FromScratch/blob/main/Optional/trial_error_alphavalues.ipynb


<br>
<br>
<br>


## Possible future improvements
To have the prediction model more closely resemble the actual made up model, feature scaling could be explored, as well as simply increasing the size of the training data, or the number of epochs during training. For reducing runtime, the existing iteration approach throghout the code, should be replaced with vectorisation (iteration was used instead of vectorisation, just to keep things easily understandable, as this is intended to be quite a simple, introductory project to machine learning).




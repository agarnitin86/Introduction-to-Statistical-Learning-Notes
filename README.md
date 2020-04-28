# Introduction-to-Statistical-Learning-Notes

[Parametric & Non-Parametric models](#parametric-non-parametric-models)

<h3 id="parametric-non-parametric-models">
Parametric Non-Parametric models
</h3>

**Difference b/w parametric & non-parametric models**
Parametric methods involve a two-step model-based approach.
1. First, we make an assumption about the functional form, or shape, of f . For example, one very simple assumption is that f is linear in X:
f (X) = β 0 + β 1 X 1 + β 2 X 2 + . . . + β p X p . (2.4)
This is a linear model, which will be discussed extensively in Chapter 3. Once we have assumed that f is linear, the problem of estimating f is greatly simplified. Instead of having to estimate an entirely arbitrary p-dimensional function f (X), one only needs to estimate the p + 1 coefficients β 0 , β 1 , . . . , β p .
2. After a model has been selected, we need a procedure that uses the training data to fit or train the model. In the case of the linear model (2.4), we need to estimate the parameters β 0 , β 1 , . . . , β p . That is, we want to find values of these parameters such that fit train 
Y ≈ β 0 + β 1 X 1 + β 2 X 2 + . . . + β p X p .

Non-parametric methods do not make explicit assumptions about the func-
tional form of f . Instead they seek an estimate of f that gets as close to the
data points as possible without being too rough or wiggly

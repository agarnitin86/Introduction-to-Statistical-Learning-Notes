# Introduction-to-Statistical-Learning-Notes

[Parametric & Non-Parametric models](#parametric-non-parametric-models)

  * [Difference b/w parametric & non-parametric models](#difference-parametric-non-parametric-models)
  
  * [Advantages/disadvantages of Parametric/Non-Parametric models](#advantages-disadvantages-of-parametric-non-parametric-models)

<h3 id="parametric-non-parametric-models">Parametric Non-Parametric models</h3>

<h4 id="difference-parametric-non-parametric-models">Difference b/w parametric & non-parametric models</h4>
Parametric methods involve a two-step model-based approach.
1. First, we make an assumption about the functional form, or shape, of f . For example, one very simple assumption is that f is linear in X:
f (X) = β 0 + β 1 X 1 + β 2 X 2 + . . . + β p X p . (2.4)
This is a linear model, which will be discussed extensively in Chapter 3. Once we have assumed that f is linear, the problem of estimating f is greatly simplified. Instead of having to estimate an entirely arbitrary p-dimensional function f (X), one only needs to estimate the p + 1 coefficients β 0 , β 1 , . . . , β p .
2. After a model has been selected, we need a procedure that uses the training data to fit or train the model. In the case of the linear model (2.4), we need to estimate the parameters β 0 , β 1 , . . . , β p . That is, we want to find values of these parameters such that fit train 
Y ≈ β 0 + β 1 X 1 + β 2 X 2 + . . . + β p X p .

Non-parametric methods do not make explicit assumptions about the functional form of f . Instead they seek an estimate of f that gets as close to the data points as possible without being too rough or wiggly

<h4 id="advantages-disadvantages-of-parametric-non-parametric-models">Advantages/disadvantages of Parametric/Non-Parametric models</h4>

Such approaches can have a major advantage over parametric approaches: by avoiding the assumption of a particular functional form for f , they have the potential to accurately fit a wider range of possible shapes for f . Any parametric approach brings with it the possibility that the  functional form used to estimate f is very different from the true f , in which case the resulting model will not fit the data well. In contrast, non-parametric approaches completely avoid this danger, since essentially no assumption about the form of f is made. But non-parametric approaches do suffer from a major disadvantage: since they do not reduce the problem of estimating f to a small number of parameters, a very large number of observations (far more than is typically needed for a parametric approach) is required in order to obtain an accurate estimate for f .

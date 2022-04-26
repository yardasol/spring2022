## Question 1:
 As noise increases, the ability to learn the underlying function decreases. Your highest sampled point is a good guess for the objective function maximum is noise is low. If noise is high, its a total crapshoot.

## Question 2:
The Gaussian Process Regressor works well if you have a large sample size. It struggles with low sample sizes unless you get lucky. Noise is a limiting factor for large sample size, wheras it does not have a siginifacnt effect on surrogate model accuracy for low sample size.

## Question 3:
Using random selection makes it harder to estimate the function for small smaple size. Randomly selecting experiments would be useful when you know a good deal about most of your parameter space and can target the randomenss to a specific region of the domain.

## Question 4:
The sequence of plots in the bottom row shows that the aquisition function converges to the maximum value quite rapidly.

## Question 5:
Exploitation doesn't change a whole lot with low iteration

Exploration works quite well.

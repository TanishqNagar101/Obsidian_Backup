#Flexiblity_vs_Interpretability
![[Pasted image 20250326153744.png]] 

					$Interpretability \varpropto \huge{\frac{ 1}{ Flexiblity}}$

- There are many ways to estimate $f$ these can be [[Linear Methods]] or [[Non-Linear Methods]] but they both share one of the two main characteristic: -
	i) Parametric Methods
		- This approach include two-steps
			- First we make an assumption about the data or the functional form of the data. Suppose we say that it is linear then: -
				$y= \beta_{1}{X_{1}}+\beta_{2}{X_{2}}+\beta_{3}{X_{3}}+...+\beta_{n}{X_{n}}\hspace{2cm}{n= no.of features}$
			- When we suppose that the $f$ is linear then we have significantly reduced the search space of the problem now all we need to estimate is $p+1\ arbitary\ cofficients(Paramertes)\ \beta_{1},\beta_{2},\beta_{3},...,\beta_{n}$.
		- While this approach is not flexible enough to produce a good fit of the data the interpretability of the model is very good. 
	ii) Non-Parametric Methods
		- This approach is computationally expansive but result in best fitting of the training data which sometime result in over fitting.
		- The search space of $f$ is significantly large result in complex computation.
		- This approach is very flexible and fit the training data perfectly but this decrease the interpretability of the model also increase the chance of overfitting.
	


#theory 
- It is done when the prediction of the output matter more than how the model arrive at that conclusion like when predicting stock market price the correct prediction is more important than how it get to that result.
- $\widehat{y}=\hat{f}(X) + \epsilon$ is the basic equation then: -
		$E[Y - \hat{Y}]^2 = E[f(X)+\epsilon - \hat{f}(X)]^2$ 
	            $= \underbrace{[f(X) - \hat{f}(X)]^2}_{\text{Reducible}} + \underbrace{Var(\epsilon)}_{\text{Irreducible}} \,$            
- Now $\hat{f}(X)$ is the one thing that we need to find/predict as $Var(\epsilon)$ show the variance caused by the irreducible error which sum up for factors like luck.
- The prediction can be done by in these ways [[How Do We Estimate f]]?
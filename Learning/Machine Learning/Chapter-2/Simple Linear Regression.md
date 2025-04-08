- Synergy / Interaction Effect: - combined effort > sum of individual effort or in simple words $\large{\large^{"}The\ Effect\ of\ X\ on\ Y\ changes\ depending\ on\ the\ value\ of\ Z^{"}}$

- Simple Linear Regression: -
	- $\large{Y\approx\beta_{0}+\beta_{1}X}$             "Regressing Y on X / Y onto X"

	- $\large{\beta_{0}\ and\ \beta_{1}\ are\ Slope\ and\ Intersept\ respectively}$
	- In simple words: -
		- $\beta_{0} \rightarrow$ It is the base value we get if we put x(input) = 0.
		- $\beta_{1} \rightarrow$ For every 1 unit of increase in X, the response value increase by $\hat{\beta_{1}}$. 
- Our goal is to find the value of $\beta_{0},\  \beta_{1}$ such that they are as close as possible to $n$ data points. The Method we are going to use to find $closeness$ is ($Least\ Square\rightarrow$[[Assessing Model Quality]]) criterion.
- Residual Sum of Square(RSS):-
	- $\large{Residual: -\ e_{i}=y_{i}-\hat{y}_{i}}$ 
	- $\large{\hat{y}_{i} = \hat{\beta}_{i}+\hat{\beta}_{i}x_{n}}$
	- $\large{RSS=e{1}^{2}+e{2}^{2}+e{3}^{2}+...+e{n}^{2}}\ \ \ \ \{ n \leftarrow No.\ of\ sample \}$ 
						or equivalent to 
	- $\large{RSS = (y_{1}-\hat{\beta}_{0}-\hat{\beta}_{1}x_{1})^{2}+(y_{2}-\hat{\beta}_{0}-\hat{\beta}_{1}x_{2})^{2}+...+(y_{n}-\hat{\beta}_{0}-\hat{\beta}_{1}x_{n})^{2}}$  
- After Minimizing it we get: -
	- $\large{\hat{\beta}_{1}} = \Huge{\frac{\sum_{i=1}^{n}(x_{i}-\bar{x})(y_{i}-\bar{y})}{\sum_{i=1}^{n}(x_{i}-\bar{x})}}$ 
	- $\large{\hat{\beta}_{0}=\bar{y}-\hat{\beta}_{1}\bar{x}}$ 
		[[RSS Minimization]]
- 
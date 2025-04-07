#bias_variance_tradeoff #error_used_in_traning_and_testing
- $\huge{variance \varpropto \frac{1}{Bias}}$
- $\huge{flexiblity \varpropto \frac{1}{interpretability}}$
- Bias: - The inability off the model to correctly fit the training data is called Bias.
	- A model with high Bias failed to capture the true relationship of the data. Hence Low Bias show good fit.
	- ![[Pasted image 20250327102541.png]]
- Variance: - The amount by which the true relationship would change on using different dataset. Ideally it should not change much.
- ![[Pasted image 20250327104521.png]]

- For training Linear mode In general we use this in training data: -           (Train MSE)
		$\large{MSE=\frac{1}{n}\sum_{i=1}^{n}}(y_{i}-\hat{f}(X_{i}))^2$ 
- For testing Linear model we use this: -                                                        (Test MSE)
		$\large{AVG(y_{0}-\hat{f}(X_{0}))}^2$ 
- The test MSE for a given value $x_{0}$ can easily decomposed into sum of three fundamental quantities: -
		$\large{E(y_{0}-\hat{f}(x_{0}))^2 = Var(\hat{f}(x_{0}))(Variance) + [Bias(\hat{f}(x_{0}))]^2(Bias Squared Error) + Var(\epsilon)(Irreducible/Bayes error)}$     
		      [[Mathematical Proof of Bias-Variance Tradeoff]]
- When there are more predictors(feature) and less sample data it is better to use "Non-Flexible" models like "linear regression" because they they will be easily able to generalize better due to bias. Vise-Versa if we have large sample data and less features then "Flexible" models like "Neural Networks or Decision Tree" would perform better.

- ![[Pasted image 20250406110914.png]]
	- Some inference from this graph: -
		a) Test error is made up of "Variance + Bias(Squared) + Irreducible(Bayes) error"
			- So at the Left end model is to simple like a straight line so it can't fit the data well therefore high bias.
			- So at the Right end the model is to complex like a amoeba curve which start to capture noise therefore high variance
			- Middle is the perfect  point of low bias and low variance.
		b) 
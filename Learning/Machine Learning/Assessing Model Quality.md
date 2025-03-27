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
		$\large{E(y_{0}-\hat{f}(x_{0}))^2 = Var(\hat{f}(x_{0})) + [Bias(\hat{f}(x_{0}))]^2 + Var(\epsilon)}$    
		      [[Mathematical Proof of Bias-Variance Tradeoff]]
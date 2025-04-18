#Mathematical_Proof
$\rightarrow \large{RSS = \sum_{i=1}^{n}(y_{i}-\hat{y}_{i})^2}$ 
$\rightarrow \large{\hat{y} = \hat{\beta}_{0}+\hat{\beta}_{1}X}$
$\rightarrow \large{J = \sum_{i=1}^{n}(y_{i}-\hat{\beta}_{0}-\hat{\beta}_{1}x_{i})^{2}}$ 
$\rightarrow \Large{\frac{\partial J}{\partial \hat{\beta}_{0}} = \sum y_{i}-n\hat{\beta}_{0} - \hat{\beta}_{1} \sum x_{i} \ \ \ \ \ \ we\ also\ multiplied\ it\ by\ 2}$

	$\large{Putting\ it\ equal\ to\ zero\ and\ Dividing\ whole\ equation\ by\ 'n', we\ get: -}$

$\Rightarrow \large{\frac{1}{n}\sum y_{i} = \hat{\beta}_{0} - \hat{\beta}_{1} \frac{1}{n} \sum x_{i}}$ 
$\Rightarrow\large{\bar{y}=\hat{\beta}_{0}-\hat{\beta}_{1}\bar{x}\ \ \ \ and\ solving\ for\ \beta_{0}\ we\ get: -}$ 
$\Rightarrow\large{\hat{\beta}_{0} = \hat{y} -\hat{\beta}_{1}\bar{x}}$ 

$\huge{Now\ solving\ for\ \beta_{1}\ we\ get: -}$ 

$\rightarrow \Large{\frac{\partial J}{\partial \hat{\beta}_{1}} = \sum(y_{i} - \hat{\beta}_{0} - \hat{\beta}_{1}x_{i})^2}$  
$\Rightarrow \large{\sum(y_{i} - \hat{\beta}_{0} - \hat{\beta}_{1}x_{i})(-x_{i}) = 0 \ \ \ \ \ we\ also\ multiply\ it\ by\ 2 }$ 

	$\Large{Putting\ the\ value\ of\ \hat{\beta}_{0}\ in\ above\ equation,\ we\ get: -}$
$\Rightarrow \large{\sum(\hat{\beta}_{1}x_{i}^{2} - \hat{\beta}_{1}\bar{x}x_{i}+x{i}\bar{y}-x_{i}y_{i}) = 0}$
	
	$\large{Now\ Solving\ for\ \beta_{1},\ we\ get: - }$
$\Rightarrow \Large{\hat{\beta}_{1} = \frac{\sum(x_{i}\bar{y} - x_{i}y_{i})}{\sum(\bar{x}x_{i} - x_{i}^{2})}}$ 
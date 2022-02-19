# Linear-mixed-effects-model

The language used is R.

The dataset MON810.csv consists of several measurements made during a subchronic toxicity study concerning the MON810 maize.
The sales1.csv consists of quarterly sales volumes (in % and indexed to the time 0) of a product.
The dataset sales30.csv now consists of quarterly sales volumes (still in % and indexed to the time 0) of 30 different products.

Based on these three datasets, I applied hypthesis testing (using Student + Fisher + Wilcoxon tests), linear regression models and linear mixed effects models. The linear mixed effects model is used on the sales30.csv dataset that contains a lot of measurements for each product. This can lead the parameters (coefficients) of a linear regression model to depend on the datapoints (the financial products in the case of sales30.csv dataset). In other terms, the linear regression parameters are no longer the same for all the datapoints. We therefore need to extend our linear model in order to take into account this inter-individual variability. That's why I used linear mixed effects models.


More details in the html file : html_compilation.html

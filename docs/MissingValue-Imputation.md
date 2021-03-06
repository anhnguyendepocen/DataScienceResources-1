# Imputation of Missing Data (or Missing Values)

Missing data can pose a challenge for a data analysis, and can limit or compromise the models and conclusions that can be drawn.

One method of dealing with missing data is through imputation.

---
### Theory and methods

[Missing data](https://en.wikipedia.org/wiki/Missing_data) -- wikipedia

Allison, P. (2000). [Multiple Imputation for Missing Data: A Cautionary Tale](http://journals.sagepub.com/doi/abs/10.1177/0049124100028003003), _Sociological Methods and Research_, 28, 301-309. ([Preprint]((http://www.ssc.upenn.edu/~allison/MultInt99.pdf)))

Fichman, Mark and Jonathon N. Cummings (2003) ["Multiple Imputation for Missing Data: Making the most of What you Know"](http://journals.sagepub.com/doi/abs/10.1177/1094428103255532), _Organizational Research Methods_, Volume: 6 issue: 3, page(s): 282-308.

Gelman, Andrew and Jennifer Hill (2006) _Data Analysis Using Regression and Multilevel/Hierarchical Models_, Cambridge University Press.
 * ["Chapter 25: Missing Data Imputation"](http://www.stat.columbia.edu/~gelman/arm/missing.pdf)

Gelman, Andrew, et al. (2014) _Bayesian Data Analysis_, (3rd edition). (see chapter 18, "Models for missing data", pp.449-467)

Karen Grace-Martin (2016?) ["Two Recommended Solutions for Missing Data: Multiple Imputation and Maximum Likelihood"](http://www.theanalysisfactor.com/missing-data-two-recommended-solutions/)

Karen Grace-Martin, ["Two Recommended Solutions for Missing Data: Multiple Imputation and Maximum Likelihood"](http://www.theanalysisfactor.com/missing-data-two-recommended-solutions/)

Neil J Perkins, Stephan R Cole, et al. (2017) ["Principled Approaches to Missing Data in Epidemiologic Studies"](https://academic.oup.com/aje/advance-article/doi/10.1093/aje/kwx348/4642951#.WhPyM47tFQc.twitter), _American Journal of Epidemiology_


Karen, The Analysis Factor, [Multiple Imputation of Categorical Variables](https://www.theanalysisfactor.com/multiple-imputation-of-categorical-variables/)

Jeff Meyer, The Analysis Factor, [Multiple Imputation for Missing Data: Indicator Variables versus Categorical Variables](https://www.theanalysisfactor.com/multiple-imputation-for-missing-data-indicator-variables-versus-categorical-variable/)

---
### R

Robert I. Kabacoff, (2011) [_R in Action: Data analysis and graphics with R_], Manning. (see chapter 15, "Advanced methods for missing data", pp.352-372)

Joseph Rickert, ["Missing Values, Data Science and R"](https://rviews.rstudio.com/2016/11/30/missing-values-data-science-and-r/), 2016-11-30

Thomas Leeper, [Multiple imputation](http://thomasleeper.com/Rcourse/Tutorials/mi.html) {tutorial for `Amelia`, `mi`, and `mice`}


["Tutorial on 5 Powerful R Packages used for imputing missing values"](https://www.analyticsvidhya.com/blog/2016/03/tutorial-powerful-packages-imputing-missing-values/) {`MICE`, `Amelia`, `missForest`, `Hmisc`, `mi`}



#### `Amelia`

**package**

CRAN page: [Amelia: A Program for Missing Data](https://cran.r-project.org/web/packages/Amelia/index.html)

vignette: [Amelia II: A Package for Missing Data](https://cran.r-project.org/web/packages/Amelia/vignettes/amelia.pdf) {PDF version}

description: [Amelia II: A Program for Missing Data](http://gking.harvard.edu/amelia)

github page for [Amelia II](https://github.com/IQSS/Amelia)


#### `BaBooN`

CRAN page: [BaBooN: Bayesian Bootstrap Predictive Mean Matching - Multiple and Single Imputation for Discrete Data](https://cran.r-project.org/web/packages/BaBooN/index.html)



#### `Hmisc`

**package**

CRAN page: [Hmisc: Harrell Miscellaneous](https://cran.r-project.org/web/packages/Hmisc/index.html)



#### `mi`

**package**

CRAN page: [mi: Missing Data Imputation and Model Checking](https://cran.r-project.org/web/packages/mi/index.html)

**articles**

Su, Gelman, Hill and Yajima (2011) [Multiple Imputation with Diagnostics (mi) in R: Opening Windows into the Black Box](http://www.stat.columbia.edu/~gelman/research/published/mipaper.pdf), _Journal of Statistical Software_, vol. 45.

Ben Goodrich and Jonathan Kropko, 2014-06-16, ["An Example of mi Usage"](https://cran.r-project.org/web/packages/mi/vignettes/mi_vignette.pdf)

#### `mice`

**package**

CRAN page: [mice: Multivariate Imputation by Chained Equations](https://cran.r-project.org/web/packages/mice/index.html)

**see also**

package `miceadds` on CRAN: [miceadds: Some Additional Multiple Imputation Functions, Especially for 'mice'](https://cran.r-project.org/web/packages/miceadds/index.html)


**articles**

Stef van Buuren & Karin Groothuis-Oudshoorn, 2011-12-12, ["mice: Multivariate Imputation by Chained Equations in R"](https://www.jstatsoft.org/article/view/v045i03), _Journal of Statistical Software_, Vol 45, Issue 3.

Michy Alice, ["Imputing missing data with R; MICE package"](https://www.r-bloggers.com/imputing-missing-data-with-r-mice-package/)

* [original source](https://datascienceplus.com/imputing-missing-data-with-r-mice-package/)

datascience+, 2015-10-04 and updated 2017-04-28, [Imputing Missing Data with R; MICE package](https://datascienceplus.com/imputing-missing-data-with-r-mice-package/)

#### `missMDA`

**package**

CRAN page: [missMDA: Handling Missing Values with Multivariate Data Analysis](https://cran.r-project.org/web/packages/missMDA/index.html)

**articles**

francoishusson, 2017-08-15, [Multiple imputation for continuous and categorical data](https://www.r-bloggers.com/multiple-imputation-for-continuous-and-categorical-data/)



#### `missForest`

**package**

CRAN page: [missForest: Nonparametric Missing Value Imputation using Random Forest](https://cran.r-project.org/web/packages/missForest/index.html)


#### `NPBayesImpute`

CRAN page: [NPBayesImpute: Non-Parametric Bayesian Multiple Imputation for Categorical Data](https://cran.r-project.org/web/packages/NPBayesImpute/index.html)


#### `VIM`

**package**

CRAN page: [VIM: Visualization and Imputation of Missing Values](https://cran.r-project.org/web/packages/VIM/index.html)

**articles**

Alexander Kowarik, Matthias Templ (2016) ["Imputation with the R Package VIM"](https://www.jstatsoft.org/article/view/v074i07), _Journal of Statistical Software_, vol. 74.



https://www.jstatsoft.org/article/view/v074i07

# Raking / Iterative Proportional Fitting

### Introduction

Includes post-stratification weights in surveying.

---
### Theory and methods

The primary method of raking is [iterative proportional fitting, or IPF](https://en.wikipedia.org/wiki/Iterative_proportional_fitting)

[IPF resources](http://www.demog.berkeley.edu/~eddieh/datafitting.html)

LCDR Lew Anderson and Dr. Ronald D. Fricker, Jr. ["Raking: An Important and Often Overlooked Survey Analysis Tool"](http://faculty.nps.edu/rdfricke/docs/RakingArticleV2.2.pdf) {PDF}

Michael P. Battaglia, David Izrael, David C. Hoaglin, and Martin R. Frankel, ["Tips and Tricks for Raking Survey Data (a.k.a. Sample Balancing)"](http://www.amstat.org/sections/srms/Proceedings/y2004/files/Jsm2004-000074.pdf) {PDF}

Andrew Gelman, [Tracking public opinion with biased polls](https://www.washingtonpost.com/news/monkey-cage/wp/2014/04/09/tracking-public-opinion-with-biased-polls/), _Washington Post_, 2014-04-09.

Eddie Hunsinger, ["Iterative Proportional Fitting For A
Two-Dimensional Table"](http://www.demog.berkeley.edu/~eddieh/IPFDescription/AKDOLWDIPFTWOD.pdf), May 2008

Sven Kurras, ["Symmetric Iterative Proportional Fitting"](http://www.jmlr.org/proceedings/papers/v38/kurras15.pdf), Appearing in Proceedings of the 18th International Conference on Artificial Intelligence and Statistics (AISTATS) 2015, San Diego, CA, USA. JMLR: W&CP volume 38.

Robin Lovelace, ["Population synthesis with R"](http://robinlovelace.net/spatial-microsim-book/smsim-in-R.html), from [_Spatial Microsimulation with R_](http://robinlovelace.net/spatial-microsim-book/)

---
### R

DIY Solution

* Christopher Waldhauser (2014-04-13) [Survey: Computing Your Own Post-Stratification Weights in R](https://www.r-bloggers.com/survey-computing-your-own-post-stratification-weights-in-r/) (at R-Bloggers)

#### `anesrake`

**package**

CRAN page: [anesrake: ANES Raking Implementation](https://cran.r-project.org/web/packages/anesrake/index.html)

**articles**

Josh Pasek (2010-03-15) ["ANES Weighting Algorithm: A Description"](https://web.stanford.edu/group/iriss/cgi-bin/anesrake/resources/RakingDescription.pdf) {PDF}

Josh Pasek, Matthew DeBell, Jon A. Krosnick (2014-07-26) ["Standardizing!and!Democratizing!Survey!Weights: The ANES Weighting System and anesrake"](http://surveyinsights.org/wp-content/uploads/2014/07/Full-anesrake-paper.pdf) {PDF}

[Raking weights with R](http://sdaza.com/survey/2012/08/25/raking/)

#### `ipfp`

**package**

CRAN page: [ipfp: Fast Implementation of the Iterative Proportional Fitting Procedure in C](https://cran.r-project.org/web/packages/ipfp/)

github page: [awblocker/ipfp](https://github.com/awblocker/ipfp)

**articles**

[Iterative proportional fitting in R (stackexchange)](http://stats.stackexchange.com/questions/59115/iterative-proportional-fitting-in-r)

#### `survey`

**package**

CRAN page: [survey: analysis of complex survey samples](https://cran.r-project.org/web/packages/survey/index.html)

homepage: [Survey analysis in R](http://r-survey.r-forge.r-project.org/survey/)

**articles**

Lumley, Thomas (2010) _Complex Surveys: A Guide to Analysis Using R_, John Wiley & Sons, Inc.

#### `{rake}` function in `survey`

**articles**

[1/2 Social Science Goes R: Weighted Survey Data](http://tophcito.blogspot.ca/2014/04/social-science-goes-r-weighted-survey.html)

[2/2 Survey: Computing Your Own Post-Stratification Weights in R](http://tophcito.blogspot.ca/2014/04/survey-computing-your-own-post.html)

[rake {survey}: Raking of replicate weight design](http://faculty.washington.edu/tlumley/old-survey/html/rake.html)


#### `weights`

**package**

CRAN page: [weights: Weighting and Weighted Statistics](https://cran.r-project.org/web/packages/weights/index.html)


**articles**



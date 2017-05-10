# Anonymity and Confidentiality
## _Or,_ Statistical Disclosure Control

### Introduction

The confidentiality of many data that are ripe for analysis are covered under some form of legal, ethical, and moral constraints. How do we as researchers ensure that the data we work with--whether it's in aggregated form or released as a micro (individual) record that is stripped of personal identifiers such as name--remains anonymous, thereby ensuring that any personal information remains private?

Many of the practical applications of statistical disclosure control can be traced back to the work of various statistical agencies around the world, who are confronted with the challenge of balancing increased expectations for openness and transparency (which translates into an increasing demand for the release of data) with "an increasing public consciousness about the privacy of individuals" (Bethlehem, 2009, p.342). 

> Statistical Disclosure Control (SDC) or Statistical Disclosure
Limitation (SDL) seeks to protect statistical data in such a way that they can be
released without giving away confidential information that can be linked to specific
individuals or entities. (Hundepool et al., 2012, p.1)

This role means much of the material on the topic comes directly or indirectly from those agencies (see, for example, the Australian National Statistical Service and Statistics Canada publications listed below).

#### Laws, Ethics, and Morals

The Canadian [Panel on Research Ethics](http://www.pre.ethics.gc.ca/eng/index/) had created a policy document that includes a chapter on [Privacy and Confidentiality](http://www.pre.ethics.gc.ca/eng/policy-politique/initiatives/tcps2-eptc2/chapter5-chapitre5/), covering the full range of concerns about the use of individual data.

---
### Discussion

[Wikipedia: Data anonymization](https://en.wikipedia.org/wiki/Data_anonymization)

Some definitions: ["What is the difference between "de-identified", "anonymous", and "coded" data?"](https://kb.wisc.edu/hsirbs/page.php?id=25351)

Justin Brickell and Vitaly Shmatikov, 2008: ["The Cost of Privacy: Destruction of Data-Mining Utility in Anonymized Data Publishing"](http://www.cs.cornell.edu/~shmat/shmat_kdd08.pdf)

{see also [Wikipedia: De-anonymization](https://en.wikipedia.org/wiki/De-anonymization)}

Arvind Narayanan and Vitaly Shmatikov, 2008: ["Robust De-anonymization of Large Datasets (How to Break Anonymity of the Netflix Prize Dataset)"](https://arxiv.org/pdf/cs/0610105.pdf)

Arvind Narayanan and Vitaly Shmatikov, 2008: ["Robust De-anonymization of Large Sparse Datasets"](https://www.cs.utexas.edu/~shmat/shmat_oak08netflix.pdf)

{see also Bruce Schneier, ["Why 'Anonymous' Data Sometimes Isn't"](http://archive.wired.com/politics/security/commentary/securitymatters/2007/12/securitymatters_1213)}

{see also Arvind Narayanan, ["Big Data: Anonymity, Privacy, Ethics"](http://randomwalker.info/data-privacy/), a collection of papers and other resources on the topic} 


Dary Hsu, ["Techniques to Anonymize Human Data"](http://blog.datasift.com/2015/04/09/techniques-to-anonymize-human-data/), 2015


Pete Warden, ["Why you can't really anonymize your data"](https://www.oreilly.com/ideas/anonymize-data-limits), 2011

Gregory J. Matthews, Pétala Gardênia da Silva Estrela Tuy, and Robert K. Arthur, 
["An examination of statistical disclosure issues related to publication of aggregate statistics in the presence of a known subset of the dataset using Baseball Hall of Fame ballots"](https://www.degruyter.com/view/j/jqas.2017.13.issue-1/jqas-2016-0085/jqas-2016-0085.xml), _Journal of Quantitative Analysis in Sports_, 2017

---
### Statistical agencies: principles and practices 

#### Australia

National Statistical Service (Australia), ["How to confidentialise data: the basic principles"](http://www.nss.gov.au/nss/home.nsf/pages/Confidentiality+-+How+to+confidentialise+data:+the+basic+principles)

National Statistical Service (Australia), ["Managing the risk of disclosure in the release of microdata"](http://www.nss.gov.au/nss/home.nsf/pages/Confidentiality+-+Managing+the+risk+of+disclosure+in+the+release+of+microdata)


#### Canada

Statistics Canada, ["Disclosure control"](http://www.statcan.gc.ca/pub/12-539-x/2009001/control-controle-eng.htm) (part of Statistics Canada [Quality Guidelines](http://www.statcan.gc.ca/pub/12-539-x/12-539-x2009001-eng.htm), Catalogue 12-539-X)

Statistics Canada, 2011: [A New Approach for the Development of a Public Use Microdata File for Canada's 2011 National Household Survey](https://www12.statcan.gc.ca/nhs-enm/2011/ref/pumf-fmgd/index-eng.cfm), Catalogue no. 99-137-XWE2015001.


#### United Kingdom

Government Statistical Service (United Kingdom), 2009:[_National Statistician’s Guidance: Confidentiality of Official Statistics_](https://gss.civilservice.gov.uk/wp-content/uploads/2012/12/Confidentiality-of-Official-Statistics-National-Statisticians-Guidance.pdf)

Government Statistical Service (United Kingdom): ["Statistical Disclosure Control"](https://gss.civilservice.gov.uk/statistics/methodology-2/statistical-disclosure-control/)

Office of National Statistics (United Kingdom), 2004: [_National Statistics Code of Practice: Protocol on Data Access and Confidentiality_](http://calls.ac.uk/wp-content/uploads/2013/06/protdataaccessconfidentiality_tcm77-179254.pdf)

#### United States of America

Bureau of Labour Statistics (BLS) Disclosure Review Board (U.S.A.), 2012: [Balancing Confidentiality Requirements with Data Users’ Information Needs](http://www.bls.gov/osmr/drb_background.pdf)

Census Bureau: [Statistical Disclosure Control (SDC)](http://www.census.gov/srd/sdc/)

* "Links and conventional references to research sponsored by the U.S. Census Bureau in the areas of statistical disclosure control, confidentiality, and disclosurelimitation."

#### Other resources

Jelke Bethlehem, 2009: [_Applied Survey Methods: A Statistical Perspective_](http://ca.wiley.com/WileyCDA/WileyTitle/productCd-0470373083.html), Wiley (Wiley Series in Survey Methodology)

* The 13th and final chapter of this comprehensive outline of survey research methods is titled "Statistical Disclosure Control". While the book focusses on data collected through sample surveys, the principles apply equally to census surveys and administrative records.

Children’s Hospital of Eastern Ontario Research Institute, 2007: [Pan-Canadian De-Identification Guidelines for Personal Health Information](https://www.priv.gc.ca/resource/cp/2006-2007/p_200607_04_e.asp)

* [Full report](http://www.ehealthinformation.ca/wp-content/uploads/2014/07/2007-Pan-Canadian-De-Identification-Guidelines.pdf)

Josep Domingo-Ferrer, 2014, ["Data Anonymization: A Tutorial"](http://www.hamilton.ie/privacy2014/josep.pdf)

Anco Hundepool, Josep Domingo-Ferrer, Luisa Franconi, Sarah Giessing, Eric Schulte Nordholt, Keith Spicer, Peter-Paul de Wolf, 2012: [_Statistical Disclosure Control_](http://ca.wiley.com/WileyCDA/WileyTitle/productCd-1119978157.html), Wiley (Wiley Series in Survey Methodology)

* Essentially a handbook of methods to ensure the privacy of individuals, it covers both microdata (individual records) and tabular data, recognizing the inherent differences in the risks associated with each.

Leon Willenborg and Ton de Wall, 1996: [_Statistical Disclosure Control in Practice_](http://www.springer.com/gp/book/9780387947228), Springer (Lecture Notes in Statistics 111).

---
### Specific methods

#### cell perturbation

Gwenda Thompson, Stephen Broadfoot, Daniel Elazar, 2013: ["Methodology for the Automatic Confidentialisation of Statistical Outputs from Remote Servers at the Australian Bureau of Statistics"](https://www.unece.org/fileadmin/DAM/stats/documents/ece/ces/ge.46/2013/Topic_1_ABS.pdf), Joint UNECE/Eurostat work session on statistical data confidentiality, Ottawa, Canada, 28-30 October 2013. 


#### k-anonymity

[wikipedia: _k_-anonymity](https://en.wikipedia.org/wiki/K-anonymity)

Latanya Sweeney, ["k-Anonymity: A Model for Protecting Privacy"](http://dataprivacylab.org/dataprivacy/projects/kanonymity/kanonymity.pdf), International Journal on Uncertainty,
Fuzziness and Knowledge-based Systems, 10 (5), 2002; 557-570. 2002

Arvind Narayanan and Vitaly Shmatikov, ["Robust De-anonymization of Large Sparse Datasets"](https://www.cs.utexas.edu/~shmat/shmat_oak08netflix.pdf) 

Roberto J. Bayardo and Rakesh Agrawal, ["Data Privacy Through Optimal k-Anonymization"](http://www.bayardo.org/ps/icde05.pdf)

Khaled El Emam and Fida Kamal Dankar, ["Protecting Privacy Using k-Anonymity"](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2528029/), J Am Med Inform Assoc. 2008 Sep-Oct; 15(5): 627–637.


#### _pq_-Rule

Meghan O’Malley, Lawrence R. Ernst, ["Practical Considerations in Applying the pq-Rule for Primary Disclosure Suppressions"](http://www.bls.gov/osmr/pdf/st070080.pdf), December 2007.

---
### R

#### `sdcMicro`

**package**

CRAN page: [sdcMicro: Statistical Disclosure Control Methods for Anonymization of Microdata and Risk Estimation](https://cran.r-project.org/web/packages/sdcMicro/index.html)

**articles**

[Statistical Disclosure Control (SDCMicro)](http://www.ihsn.org/home/software/disclosure-control-toolbox) at International Household Survey Network.

Matthias Templ, ["Statistical Disclosure Control for Microdata Using the R-Package sdcMicro"](http://www.tdp.cat/issues/tdp.a004a08.pdf), _Transactions on Data Privacy_ 1 (2008) 67–85.

Matthias Templ, Bernhard Meindl and Alexander Kowarik, [Introduction to Statistical Disclosure Control (SDC)](https://cran.r-project.org/web/packages/sdcMicro/vignettes/sdc_guidelines.pdf), 2015

Alexander Kowarik and Matthias Templ, ["Make Your Data Confidential with the sdcMicro and sdcMicroGUI packages"](https://www.researchgate.net/publication/261507879_Make_Your_Data_Confidential_with_the_sdcMicro_and_sdcMicroGUI_packages), 2012

#### `sdcMicroGUI`

**package**

CRAN page: [sdcMicroGUI: Graphical User Interface for Package 'sdcMicro'](https://cran.r-project.org/web/packages/sdcMicroGUI/index.html)

**articles**

Matthias Templ, Bernhard Meindl and Alexander Kowarik, [Tutorial for sdcMicroGUI (and sdcMicro)](https://cran.r-project.org/web/packages/sdcMicroGUI/vignettes/gui_tutorial.pdf), 2015


---
### Other tools

Benjamin Bengfort, ["A Practical Guide to Anonymizing Datasets with Python & Faker: How Not to Lose Friends and Alienate People"](http://blog.districtdatalabs.com/a-practical-guide-to-anonymizing-datasets-with-python-faker), 2016


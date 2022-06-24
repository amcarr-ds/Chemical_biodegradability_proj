# Cool Project Title Name :rocket:

#### -- Project Status: [In Progress]

## Project Intro/Objective (In Progress)
Determining whether a specific chemical is biodegradable is an invaluable tool in the analysis of its overall effect on the environment, as it is a characteristic that when tied to other chemical features like toxicity, can theoretically have long-lasting impacts on natural habitats (Boethling et al., 2007). As such, having a way to predict ready biodegradability based on other molecular features of a compound, especially during the development of new substances, could help prevent the release of chemicals into the environment that will stay there for great lengths of time. Mansouri et al. (2013a) published results on the application of several predictive modeling techniques to dichotomously classify chemicals into ready biodegradable or not. This current study uses the same final data set (*N* = 1,055) and has two main objectives: 1) Perform modeling that serves to reproduce the methods and results of Mansouri et al., specifically related to the *K*NN, PLSDA, and SVM models—note, the consensus models are not assessed in this particular paper; and 2) Implement modeling techniques novel to this specific data set, in order to assess both whether predictive performance can be increased, as well as whether a less complex model (i.e., logistic regression (LR)) would at least match previous performance, but allow increased interpretability. As such, the general hypotheses are: 1) Through model tuning and application of novel approaches, higher rates for both specificity (aka true negative rate) and sensitivity (aka true positive rate) can be achieved relative to Mansouri et al.; 2) While examining an additional evaluation measure, the receiver operating characteristic (ROC) curve, an area under the curve (AUC) of greater than 90% can be achieved; and 3) At least one novel model (e.g., LR, linear discriminant analysis (LDA), nearest shrunken centroids (NSC)) will provide more useful insight into how it works through higher interpretability.

### Team Members
* Aaron Carr
* Ivan Chavez
* Sreeja Kurapaty


### Methods Used (still under consideration)
* Predictive Modeling
* Classification
* etc.

### Technologies
* R
* R Packages?
* R Shiny?



## Project Description (In Progress)

## Needs of this project (In Progress)
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- model performance evalutions
- writeup/reporting
- etc..

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](data) within this repo.
3. Data processing/transformation scripts are being kept [here](notebooks)
4. Stats and general reference tables are being kept [here](outputs)

## Featured Notebooks/Analysis/Deliverables (In Progress)

## References (Cite final dataset used here)
- Boethling, R. S., Sommer, E., & DiFiore, D. (2007). Designing small molecules for biodegradability. *Chemical Reviews*, *107*(6), 2207–2227. https://doi.org/10.1021/cr050952t
- Mansouri, K., Ringsted, T., Ballabio, D., Todeschini, R., & Consonni, V. (2013a). Quantitative structure-activity relationship models for ready biodegradability of chemicals. *Journal of Chemical Information and Modeling*, *53*, 867–878. https://doi.org/10.1021/ci4000213
- Mansouri, K., Ringsted, T., Ballabio, D., Todeschini, R., & Consonni, V. (2013b). *QSAR biodegradation* [Data set]. UCI Machine Learning Repository. http://archive.ics.uci.edu/ml/datasets/QSAR+biodegradation#


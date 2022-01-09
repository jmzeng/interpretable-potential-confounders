# Uncovering interpretable potential confounders from clinical text

This repository presents a simple pipeline that can be used to uncover potential interpretable confounders from clinical text. 

Due to IRB restrictions, we cannot share the data needed to demonstrate the code. We share the R analysis pipeline post data-processing as an example of how to implement our method. The existing code is developed on R version 4.0.2. 

## Instructions:
To run the pipeline, please process your dataset of choice for treatment surivival analysis. The code requires a data input with at least the following fields:

* W: indicator of binary treatment
* Y: time-to-event outcome
* D: indication of event of interest
* X: set of covariates 

For selection of interesting potential confounders, it is recommneded to include as many covariates as the size of the dataset allows. The set of covariates can be selected from structured data and unstructured data. For details on how to process the unstructured data, please refer to the paper. 

Please see our full paper on medArxiv:
Zeng, J., Gensheimer, M. F., Rubin, D. L., Athey, S., & Shachter, R. D. (2021). Uncovering interpretable potential confounders in electronic medical records. medRxiv. https://www.medrxiv.org/content/10.1101/2021.02.03.21251034v3

For questions, please contact Jiaming Zeng at jiaming (at) alum.stanford.edu. 
We thank Allison Koenecke (https://infosci.cornell.edu/~koenecke/) for lending us a basis for the R Code.

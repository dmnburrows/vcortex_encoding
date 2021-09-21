# vcortex_encoding

Repo for analysing dimensionality of spontaneous and evoked activity, and encoding of stimuli in the layers of the visual cortex, using dimensionality reduction, logistic and linear regression. This is a work in progress! 

Using data from Stringer et al. : https://pubmed.ncbi.nlm.nih.gov/31000656/

## What is this repo for?
* the analysis of spontaneous and evoked activity in visual cortex of mice
* the prediction of stimuli from responses to infer the amount of information held in each cortical layer

## What does this repo contain?
Modules contain functions for analysing cortical data
Accompanying ipynotebooks demonstrate how to use the modules

## Modules
'admin_functions.py' - useful administrative functions

## Notebooks
'cortex_layer_dim.ipynb' - analysing the dimensionality of each cortical layer in spont and evoked activity

'cortex_layer_minidomains.ipynb' - assessing the presence of minidomains that share orientation preferences 

'cortex_layer_orient_linreg.ipynb' - using linear regression to predict stimulus orientation from activity

'cortex_layer_orient_logreg.ipynb' - using logistic regression to predict stimulus orientation from activity

'cortex_layer_orient_PCpred.ipynb' - using PCs to predict stimulus orientation from activity



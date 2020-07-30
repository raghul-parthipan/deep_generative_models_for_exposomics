# Read Me

This is a repository for my MRes thesis using deep generative models for exposomics data. 

It can be navigated as follows:

## Parent directory ##

- *requirements.txt* gives the required packages. 

- In all notebooks, paths will need to be updated based on where data is and where you want models to be saved. 

## preprocessing ##

- This folder contains a notebook, *data_processing_notebook.ipynb*, where data preprocessing was done. 

- *FeatureSelection_CV.ipynb* was used for feature selection. The selected features are given in *feature_selection.npy*, in the parent directory.

## models ##

- **M2** contains the files relating to the best M2 model. Likewise for **M2C**

## M2 ##

- There are three notebooks (starting with "Generative...") which implement the three M2 variants. These notebooks are the heart of this repository. Each notebook begins by defining useful functions. The architecture of the models are then defined, including custom components. Loss functions are specified along with training procedures. A hyperparameter search is conducted, before a single model is finally trained and saved. 

- The Discriminator notebook is used to assess the realism of the generated data.

- The Results notebook creates the results as seen in the MRes thesis.

## M2C ##

 - The file structure is identical to above. 



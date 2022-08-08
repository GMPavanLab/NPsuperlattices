# NPsuperlattices

This repository contains the set of data shown in the paper "Reconstitution of microtubule into GTP-responsive nanocapsules".

All the input data needed to run the simulations and get the results are organized in 2 different folders:

 * `1 - CoarseGrainedSimulations/`

	in this folder there are all the Gromacs input files necessary to reproduce the coarse-grained simulations shown in the article.
        
 * `2 - SOAP&PAMM-Analysis/`

	this folder contains an example case and the scripts to reproduce the SOAP and PAMM analysis discussed in this work. In particular, the example (`ExampleCase-300K-E=0.05/`) is referred to the simulation at T = 300 K and E = 0.05 V/nm, and containd the reduced trajectories - necessary for the further analysis. From the Jupyter script `get_soap.ipynb` it is possible to implement the SOAP analysis ,from the script `get_pca.ipynb` it is possible to evalue the PCA analysis, and from the script `pamm_clustering.ipynb` it is possible to perform the PAMM clustering analysis. 


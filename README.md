# recom_sys_qm9

Traditional molecular recommendation systems often fail to rank candidates effectively because of the large and sparse space of possible molecules. This repository presents a new approach that integrates a Variational Graph Autoencoder (VGAE) with a transformer-based model. The VGAE learns a latent representation of molecules where structurally and chemically similar compounds are close together. From this space, new candidates are sampled in the neighborhood of a specific SMILES string, ensuring chemical relevance. The transformer-based model then evaluates their properties (i.e., Atomization Energy, AE), reducing sparsity and enabling more accurate ranking of recommendations.


![Graphical Abstract](A_Recommender_System.svg)

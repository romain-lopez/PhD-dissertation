# Ph.D. dissertation: Charting Cellular States, One Cell at a Time: Computational, Inferential and Modeling Perspectives
- Author: Romain Lopez
- Supervisors: Michael I. Jordan and Nir Yosef

## Download
Submitted. Available soon on eScolarships.org

## Abstract
In this thesis, we pursue the design of Bayesian models as well as large-scale approximate inference procedures for the analysis of single-cell transcriptomics data. 

First, we rely on Bayesian statistics to formalize several central algorithmic steps of single-cell transcriptomics data analysis. In particular, we introduce single-cell Variational Inference (scVI), a deep generative model that separates technical noise from biological signal, and is readily applicable de novo cell type identification, batch effect correction, and differential expression. As follow-up work, we introduce single-cell ANnotation using Variational Inference (scANVI), an extension of scVI for sharing annotation of cells across experimental conditions. scANVI is a fully-probabilistic method for harmonizing collections of single-cell RNA sequencing datasets, and therefore provides a principled way of quantifying the uncertainty of cell state annotation. The inference procedure for both methods is based on auto-encoding variational Bayes and scales to millions of cells.  

In a second line of work, we expose two pathological behaviors of variational inference we encountered while developing scVI. First, the presence of an encoder network leads to entanglement of the latent variables, an undesirable behavior for factoring out unwanted variations from embeddings. To address this problem, we introduce the Hilbert-Schmidt Information Criterion (HSIC) constrained Variational Autoencoder (VAE), a generic variant of the VAE that incorporates a non-parametric measure of dependence as an explicit constraint for the variational distribution. Second, we expose the unsuitability of the variational distribution for Bayesian decision-making and introduce a simple procedure for making more accurate decisions with VAEs. In particular, we explore alternative training procedures, based on using separate variational bounds for learning the generative model and variational posterior. 

## Contact
romain[underscore]lopez[at]berkeley.edu

# Comparison of protein sequence embeddings

This repository contains the data and code used in the study entitled
*"Transfer learning in proteomics: comparison of novel learned representations
for protein sequences,"* by E. Fenoy, A. Edera and G. Stegmayer (under
review). Research Institute for Signals, Systems and Computational
Intelligence, [sinc(i)](https://sinc.unl.edu.ar).

<p align="center">
<img src="./img/premb_projs.png" width="900"/>
</p>


## Intro

Representation learning techniques are being used for encoding different types
of protein information (sequence, domains, interactions, etc.) as
low-dimensional vectors. In this study, we performed a detailed comparison of
several protein sequence embeddings on several bioinformatics tasks:

* determining similarities between proteins in the embeddings projected space.

* inferring protein domains.

* predicting ontology-based protein functions.


## Protein sequence embeddings

This [link](https://drive.google.com/drive/folders/10lBH8WLrSqS2Mjz6m-QpTBeOmWZbOKHF) contains the protein
sequence embeddings used for all the analyses in the studies.

## Notebook

This
[notebook](https://colab.research.google.com/github/sinc-lab/Comparison-of-Protein-learning/blob/main/notebooks/01_projections_with_PFAM_domains.ipynb)
reproduces the analysis showing the capability of protein sequence embeddings
for capturing protein domain information.

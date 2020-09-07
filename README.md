# Prematurity_SupplementaryMaterial


This repository contains supplementary materials relating to the manuscript 
"Gestational-age dependent development of the neonatal metabolome" by M. Ernst ([@madeleineernst](https://github.com/madeleineernst)), 
S. Rogers ([@sdrogers](https://github.com/sdrogers)), U. Lausten-Thomsen, A. Bjorkbom, S.S. Laursen, J. Courraud, 
A. Børglum, M. Nordentoft, T. Werge, P. B. Mortensen, D. M. Hougaard, A.S. Cohen.

## CorrelationAnalysis

This folder contains the Jupyter notebook used to assess and plot univariate correlation at the individual metabolite level using Kendall’s Tau (Supplementary Data 1). 

## Heatmap

This folder contains the Jupyter notebook used to create a heatmap of all annotated features significantly related to gestational age by univariate correlation analysis, hypergeometric testing at the molecular family level or LASSO regression. 

## HyperGeometricTesting

This folder contains the Jupyter notebook used to identify chemically structurally related molecular families through hypergeometric testing overrepresented with metabolites correlating with gestational age. 

## IonRichness_ShannonDiversity

This folder contains the Jupyter notebook used to calculate Shannon diversity and ion richness (Figure 1c Supplementary Figures 2 and 3).

## LASSO

This folder contains the Jupyter notebook adapted from [Wilamnski and collaborators (2019)](https://www.nature.com/articles/s41587-019-0233-9) available at: [https://github.com/PriceLab/ShannonMets](https://github.com/PriceLab/ShannonMets) used to predict gestational age from the neonatal metabolome using a tenfold cross-validation (CV) implementation of the least absolute shrinkage and selection operator method (LASSO). 

## PCoA

This folder contains the Jupyter notebook used to create the principal coordinates analysis (PCoA) plot with the Bray-Curtis dissimilarity and the Permutational Multivariate Analysis of Variance (PERMANOVA) used to assess the variation in the metabolome explained by gestational age. 

## SpectralMirrorPlots

This folder contains the Jupyter notebook used to create spectral mirror plots of the forty chemically structurally annotated compounds through GNPS library matching correlating significantly with gestational age (false-discovery-rate-adjusted P < 0.05). Data were extracted automatically using the metabolomics USI tool (http://metabolomics-usi.ucsd.edu/) and mirror plots produced in Python using the spectrum_utils package ([Wout (2020)](https://pubs.acs.org/doi/full/10.1021/acs.analchem.9b04884)) (Supplementary Data 2).

## VennDiagram

This folder contains the Jupyter notebook used to create the Venn diagram illustrating overlapping metabolites significantly associated with gestational age by univariate correlation analysis, hypergeometric testing at the molecular family level and LASSO regression (Figure 1d).


## Citation

[Ernst M, Rogers S, Lausten-Thomsen U, Bjorkbom A, Laursen SS, Courraud J, Borglum A, Nordentoft M, Werge T, Mortensen PB, Hougaard DM, Cohen AS. Gestational-age dependent development of the neonatal metabolome. 2020; medRxiv](https://www.medrxiv.org/content/10.1101/2020.03.27.20045534v1).

[Wilmanski T, Rappaport N, Earls JC et al. Blood metabolome predicts gut microbiome a-diversity in humans. Nature biotechnology 2019; 37: 1217-1228](https://www.nature.com/articles/s41587-019-0233-9).

[Wout B, spectrum_utils: A Python Package for Mass Spectrometry Data Processing and Visualization. Anal. Chem. 2020; 92: 659-661.](https://pubs.acs.org/doi/full/10.1021/acs.analchem.9b04884)


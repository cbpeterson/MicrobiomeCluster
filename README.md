## MicrobiomeCluster

### Author: Yushu Shi

- **Reference**: Shi Y, Zhang L, Peterson CB<sup>&ast;</sup>, Do K<sup>&ast;</sup>, Jenq RR<sup>&ast;</sup>. (2022) Performance determinants of unsupervised clustering methods for microbiome data. *Microbiome*. 10(25):1-12. <sup>&ast;</sup>Authors contributed equally
- This package includes basic functions for calculating operational taxonomic unit (OTU) and cluster of related taxonomic units (CROTU) abundances. It also provides distance and levels of tree nodes and tips from its root. Researchers can use the MicrobiomeCluster package to manipulate an existing tree by trimming or growing branches, or check if a Beta metric is suitable for clustering a dataset.

#### Key functions:

- **combMetric**: compute the robust weighted combination of Bray-Curtix dissimilarity and unweighted Unifrac dissimilarity
- **dist2Root**: calculate the distance from leaf nodes to the root
- **level2Root**: calculate the number of tree levels from leaf notes to the root

Additional functions for manipulating an existing tree are provided in the R package.

#### Datasets:

OTU tables and key covariates are provided for three-real world data sets:

- **Martinez**: Martinez I, Stegen JC, Maldonado-Gomez MX, Eren AM, Siba PM, Greenhill AR, Walter J. (2015) The gut microbiota of rural Papua New Guineans:
composition, diversity patterns, and ecological processes. *Cell Reports*. 11(4):527-38.
- **Schnorr**: Schnorr SL, Candela M, Rampelli S, Centanni M, Consolandi C, Basaglia G, et al. (2014)
Gut microbiome of the Hadza hunter-gatherers. *Nature Communications*. 5(1):1-2.
- **Smits**: Smits SA, Leach J, Sonnenburg ED, Gonzalez CG, Lichtman JS, Reid G, Knight R, et al. (2017)
Seasonal cycling in the gut microbiome of the Hadza hunter-gatherers of Tanzania. *Science*. 357(6353):802-6.

# Description

The chart above maps the outcome of gene expression after performing principal component analysis, plotted in two dimensions using two principal components. The user may choose of number of PCA dimensions to display as well as the metadata key by which to color. The amount of dimensions (#1-7) are ordered by their relevance, PCA 1 having the most variation and PCA 7 having the least.

# Data Input

The input data to this visualization is an [expression matrix](http://www.broadinstitute.org/cancer/software/gsea/wiki/index.php/Data_formats#TXT:_Text_file_format_for_expression_dataset_.28.2A.txt.29) and a metadata file (TSV or CSV format). The rows of the expression matrix must be the observations (e.g. probes, genes) and the columns must be the variables (e.g. samples). The metadata file must must be a list of metadata for each variable in the matrix file, and in the same order.

# Example Data

[What is principal component analysis?, Ringnér 2008 ](http://www.nature.com/nbt/journal/v26/n3/full/nbt0308-303.html) discusses the importance of Principal Component Analysis in biology and genetics.  This paper refers to
[Saal et al.](http://www.pnas.org/content/104/18/7564) in which the expression of 27,658 genes in 105 breast tumor samples were measured (available [here](http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5325)).  Ringnér
 applied Principal Component Analysis to the 8,534 probes with expression measurements for all 105 samples. This example chart serves to confirm the results, but user-supplied data can also be used in this interface.

# Acknowledgements

This visualization was made by [Thor Wahlestedt](https://github.com/thorWahlestedt) at RIKEN in Yokohama, Japan with the aid of [Jayson Harshberger](https://github.com/Hypercubed).

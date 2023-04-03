# Genetic-analysis-of-Down-s-syndrome-in-mice
I use logistic regression to predict biological characteristics ("phenotypes") from gene expression data. 
Genes are the basic unit in the DNA and encode blueprints for proteins. When proteins are synthesized from a gene, the gene is said to "express". Micro-arrays are devices that measure the expression levels of large numbers of genes in parallel. By finding correlations between expression levels and phenotypes, scientists can identify possible genetic markers for biological characteristics.

The data for this comes from:

https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression

In this data, mice were characterized by three properties:

Whether they had down's syndrome (trisomy) or not
Whether they were stimulated to learn or not
Whether they had a drug memantine or a saline control solution.
With these three choices, there are 8 possible classes for each mouse. For each mouse, the expression levels were measured across 77 genes. We will see if the characteristics can be predicted from the gene expression levels. This classification could reveal which genes are potentially involved in Down's syndrome and if drugs and learning have any noticeable effects.

To get the results of this experiment run the notebook gene.ipynb


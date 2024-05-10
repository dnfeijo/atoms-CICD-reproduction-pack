# atoms-CICD-reproduction-pack
This is a Reproduction Package made for the paper
"Studying the Impact of CI/CD Adoption on Atoms 
of Confusion Distribution and Prevalence in Open-Source Projects",
submitted for review to the Journal of Software Engineering Research and Development
by the Authors:
- Diego N. Feijó
- Carlos D. A. de Almeida
- Lincoln S. Rocha

This document is a general helper for those wanting
to replicate our experiment. The data we used is included,
but you may use other data if inclined.

1. First of all, make sure that you have all Python3 installed.
2. Second of all, make sure that you install the necessary dependencies
for our imports to work.
3. Following that, execute the "atoms-longlived" and "atoms-android" notebooks
4. Then, execute the "comparison" notebooks to get the data comparison and Wilcoxon results for mean and median
5. After that, execute "history-plots-geo-mean" to get the plots showing the history of each metric for each project, and also the Wilcoxon comparison using the geometric mean
6. Finally, execute the "violin-plots-fp-rp" to get the violin plots and the metrics FP and RP

All the plots will be in the Output folder,
and all the .csv files will be in the Data folder.
The original .csv files for each project will be in a subfolder
in Data called "reports".

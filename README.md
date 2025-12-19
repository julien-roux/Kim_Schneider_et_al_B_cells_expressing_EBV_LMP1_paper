# Myelin antigen capture in the CNS by B cells expressing EBV latent membrane protein 1 leads to demyelinating lesion formation

This Github repository provides code, necessary data and R package environment allowing to reproduce the single-cell and bulk RNA-seq analyses presented in Kim, Schneider et al., 2026 Cell [ADD LINK}

The RNA-seq data (bulk and single-cell) are available from GEO: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE308213

After cloning the repository from Github, you can create and activate the conda environment using:

```
cd Kim_Schneider_et_al_B_cells_expressing_EBV_LMP1_paper
## Then, start R 
R --vanilla
## Within R install required packages
install.packages("renv")
renv::restore()
## Run the code and generate an HTML document including the figures from the paper
rmarkdown::render("Kim_Schneider_et_al_B_cells_expressing_EBV_LMP1_paper.Rmd")
```

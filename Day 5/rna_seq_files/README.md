# RNA-Seq Tutorial 6/20/2023
These are the materials for the RNA-seq tutorial taught at Makerere University in June 2023. Hopefully they are helpful!

## Installations: 

You will first need R and RStudio:

https://www.r-project.org

https://posit.co/download/rstudio-desktop/

You will need to install the following R packages:

	if (!requireNamespace("BiocManager", quietly = TRUE))
		install.packages("BiocManager")
	BiocManager::install("Rsubread")
	BiocManager::install("Rsamtools")

You may also want to install the following for downstream analysis: 

	install.packages("devtools")
	devtools::install_github("wevanjohnson/singleCellTK")



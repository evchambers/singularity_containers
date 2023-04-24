# Singularity image container definition file for R/Seurat v5

* Ubuntu 22.04
* R 3.4.0
* Tidyverse v2.0.0
* Seurat v5 (Seurat_4.9.9.9042)

This container is for running single cell RNA-seq analysis in `R/Seurat`. Please see Satija Lab [GitHub page](https://github.com/satijalab/seurat) for more documentation.

https://satijalab.org/seurat/articles/get_started_v5.html

Download the .def file and build the containiner using

`sudo singularity build Seurat5.sif R_Seurat.def`

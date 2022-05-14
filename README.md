These are the codes used for analysis and figure generation in the preprint manuscript "Pubertal sex hormones control transcriptional trajectories in the medial preoptic area" (Hashikawa, Hashikawa et al. 2021) from the Stuber lab.

The joint analysis and DEG analysis are based on Seurat v3 package from Satija lab. Detail tutorial can also be found in their website https://satijalab.org/seurat.
The robustness of our clustering was tested using LISI https://github.com/immunogenomics/LISI and clustree https://cran.r-project.org/web/packages/clustree/vignettes/clustree.html packages. 

Trajectory analysis is based on Monocle 3 package from Trapnell lab https://cole-trapnell-lab.github.io/monocle3 and on MELD package from Krishnaswamy lab https://github.com/KrishnaswamyLab/MELD. 

Regulatory analysis is based on SCENIC package from Aerts lab https://github.com/aertslab/SCENIC and scWGCNA package established by Sam Morabito https://smorabit.github.io/tutorials/9_scWGCNA_tutorial/.

The analysis starts from the "Doublet Detection" code with the data deposited at GEO :GSE172177. https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE172177. The data will be publicly available once the manuscript is published.

Deposited data is gene-count matrix data which was generated by processing the FASTQ files through cellranger pipeline for alignment.

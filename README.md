#### Multi-omics molecular profiles based on TCGA-data and scRNA-seq data

```
/home/guosa/hpc/project/thyroid/scRNA
/home/guosa/hpc/methylation/Pancancer/methdata.pancancer.RData
/home/guosa/hpc/methylation/Pancancer/RNA-seq/rnaseqdata.pancancer.RData
```

Timeline:

* load methylation data (485577x9756) and identify thyroid cancer samples and clinical information
* Background: scRNAseq has been used to identify novel cell-by-cell machanisum for cancer heterogneity research. we collected shared genes (200 genes) between scRNAseq and TCGA dataset and found they could show some similiar patterns and therefore we cluster TCGA samples into 5 different group which is quite different between the previous TCGA-Cell paper. 
* three samples were excluded from the study: TCGA-EM-A3O9, TCGA-ET-A25J, TCGA-ET-A3DT
* start the project and save all the data and result to `/home/guosa/hpc/project/thyroid/scRNA`

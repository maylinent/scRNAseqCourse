# scRNAseqCourse
SLURM scripts of the scRNAseq data analysis course 2026, by Mayline Goëb

## Content of repository
| **File** | **Description** |
|------|-------------|
|1) Data preparation | Download, uncompress a reference genome and a bulk RNAseq raw data|
|2) Trim | trimming of raw data to remove adapters|
|3) fastQC | fastQC quality check of raw reads|
|4) STAR | STAR alignment of RNAseq reads to a reference genome|
|featureCounts | reads counts of gtf file|
|eggnog | eggnogmapping annotation if no reference genome available|
|CellRanger | cellranger alignment to be processed on Rstudio|

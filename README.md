# Mapping The Ontogeny Of Human Hematopoietic Stem Cells From Definitive Hemogenic Endothelium To Birth

## Overview
The map of human hematopoietic stem cell (HSC) ontogeny is incomplete due to a lack of reliable methods to identify HSCs as they emerge and mature in different hematopoietic sites. We created a single-cell transcriptome map of hemato-vascular cells in human hematopoietic tissues from early 1st trimester to birth, and found that co-expression of RUNX1, HOXA9, MLLT3, MECOM, HLF and SPINK2 distinguishes definitive HSCs from progenitors throughout gestation. In addition to the AGM region, nascent HSCs populated the placenta and yolk sac before colonizing the liver. Comparison of HSCs from different developmental stages revealed the establishment of a stable HSC transcription factor machinery at HSC emergence, whereas the surface marker phenotype changed profoundly throughout development. HSC transition to the liver after 6 weeks marked a major shift in HSC molecular properties, as HSCs suppressed endothelial, megakaryocytic and myeloid surface phenotype associated with nascent HSC identity, and acquired HSC maturation markers PROM1/CD133 and HLA-DR concomitant to attaining HSC functional properties. The origin of definitive HSC was tracked to HOXA patterned ALDH1A1+ KCNK17+ definitive hemogenic endothelial cells, which arose from IL33+ALDH1A1+ arterial endothelial cells on the ventral side of dorsal aorta, as confirmed by visual transcriptomics. The in vivo map of human HSC development was utilized to validate the generation of AGM-stage definitive HSPC in vitro from human pluripotent stem cells, and can be employed to guide their maturation to functional HSCs.

## Scripts, R objects and metadata
The R script, R objects and the metadata file are shared via google drive due to their size. The metadata file contains the cell barcode, the original sample identity, the Seurat cluster identity, the number of genes and UMIs detected, and the percentage of mitochondrial expression. <br/>
These files can be accessed [here.](https://drive.google.com/drive/folders/1bsl4HMPh0ZZb9iAZTXD5lVY56sNj_MCm?usp=sharing) <br/>
The [Inventory.csv](https://github.com/mikkolalab/Human-HSC-Ontogeny/blob/main/Inventory.csv) file in this GitHub page associates the folder names on Google Drive to the figure numbers in the manuscript.

## ACTINN Reference dataset
The expression matrix and the celltype annotation of the ACTINN Reference dataset can be accessed  [here.](https://drive.google.com/drive/folders/1NN5oISFii2vFhYuWZMNzanj6iLIpsZzS?usp=sharing)

## Loupe files for the spatial-seq samples
We used the loupe files to visualize gene expression in the spatial-seq samples. The loupe files can be accessed  [here.](https://drive.google.com/drive/folders/17bnNG-cd0-4RXLImHYWX_mgaMMIvk_xF?usp=sharing)

## Cluster marker genes for the spatial-seq samples
We clustered the spatial-seq samples using the Seurat pipeline. The cluster markers for each section can be accessed. For each cluster in each section, we also performed cell type prediction analysis with the cluster marker genes using Enrichr. The enriched cell type predictions are saved in different tabs in the excel file. 

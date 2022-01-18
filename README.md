# Mapping Human Hematopoietic Stem Cells from Hemogenic Endothelium to Birth

## Overview
Human hematopoietic stem cell (HSC) ontogeny is poorly defined due to the inability to identify HSCs as they emerge and mature in different hematopoietic sites. We created a single-cell transcriptome map of human hematopoietic tissues from 1st trimester to birth and found that HSC signature RUNX1+HOXA9+MLLT3+MECOM+HLF+SPINK2+ distinguishes HSCs from progenitors throughout gestation. In addition to the AGM (aorta-gonad-mesonephros) region, nascent HSCs populated the placenta and yolk sac before colonizing the liver at 6 weeks. Comparison of HSCs from different maturation stages revealed the establishment of HSC transcription factor machinery upon HSC emergence, whereas their surface phenotype evolved throughout development. HSC transition to the liver marked a molecular shift evidenced by suppression of surface antigens reflecting nascent HSC identity and acquisition of HSC maturity markers PROM1/CD133 and HLA-DR. HSC origin was tracked to ALDH1A1+KCNK17+ hemogenic endothelial (HE) cells, which arose from IL33+ALDH1A1+ arterial endothelial subset, termed pre-HE. Spatial transcriptomics and immunofluorescence visualized this process in intra-aortic hematopoietic clusters on the ventral side of the dorsal aorta. The in vivo map of human HSC ontogeny validated the generation of AGM-like definitive HSPCs from human pluripotent stem cells, and serves as a guide to improve their maturation to functional HSCs.

## Scripts, R objects and metadata
The R script, R objects and the metadata file are shared via google drive due to their size. The metadata file contains the cell barcode, the original sample identity, the Seurat cluster identity, the number of genes and UMIs detected, and the percentage of mitochondrial expression. <br/>
These files can be accessed [here.](https://drive.google.com/drive/folders/1bsl4HMPh0ZZb9iAZTXD5lVY56sNj_MCm?usp=sharing) <br/>
The [Inventory.csv](https://github.com/mikkolalab/Human-HSC-Ontogeny/blob/main/Inventory.csv) file in this GitHub page associates the folder names on Google Drive to the figure numbers in the manuscript.

## Scripts for the scorecards
There are many dotplots in the manuscript serving as scorecards to define cell identities. To make it easier to reproduce these cell types, the R script file containing the gene lists and codes to make the dotplots can be accessed [here.](https://github.com/mikkolalab/Human-HSC-Ontogeny/blob/main/scorecards%20scripts.R) The first four lines in the script describes how the dotplots can be plotted.

## ACTINN Reference dataset
The expression matrix and the celltype annotation of the ACTINN Reference dataset can be accessed  [here.](https://drive.google.com/drive/folders/1NN5oISFii2vFhYuWZMNzanj6iLIpsZzS?usp=sharing)

## Loupe files for the spatial-seq samples
We used the loupe files to visualize gene expression in the spatial-seq samples. The loupe files can be accessed  [here.](https://drive.google.com/drive/folders/17bnNG-cd0-4RXLImHYWX_mgaMMIvk_xF?usp=sharing)

## Cluster marker genes for the spatial-seq samples
We clustered the spatial-seq samples using the Seurat pipeline. The cluster markers for each section can be accessed [here.](https://github.com/mikkolalab/Human-HSC-Ontogeny/tree/main/Visium%20samples%20cluster%20markers) For each cluster in each section, we also performed cell type prediction analysis with the cluster marker genes using Enrichr. The enriched cell type predictions are saved in different tabs in the excel file. 

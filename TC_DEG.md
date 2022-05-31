# A workflow of identifying Time-course differentially-expressed genes (TC-DEGs)

Time-course differentially-expressed genes (TC-DEGs) are genes with changes in expression depend not only on conditions, but also on times. In our lab, we have established a workflow to identify TC-DEGs from time-series RNAseq data between two conditions (e.g. KO vs WT, treatment vs control). This workflow first categorize TC-DEGs into several clusters by k-means clustering and perform pathways analysis to identify the enriched biological pathway for each cluster.

![TD-DEGs](Figs/TC_DEG.jpg)

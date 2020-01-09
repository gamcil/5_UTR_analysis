# 5_UTR_analysis

Code accompanying the paper: 

> CRISPRa of biosynthetic gene clusters for bioactive molecule discovery in filamentous fungi
> Indra Roux, Clara Woodcraft, Jinyu Hu, Rebecca Wolters, Cameron L.M. Gilchrist, Yit-Heng Chooi

## Data
All analysis was performed using version 46 of the *A. nidulans* FGSC A4 genome
 obtained from [FungiDB](https://fungidb.org/common/downloads/Current_Release/AnidulansFGSCA4/)
 (FungiDB-46_AnidulansFGSCA4_Genome.fasta and FungiDB-46_AnidulansFGSCA4.gff).

## File summary
| File | Description |
| ---- | ----------- |
| notebook.ipynb | Jupyter notebook containing all code used in analyses |
| five_prime_UTRs_genome.csv | Summary of 5'UTRs for all genes in *A. nidulans* |
| five_prime_UTRs_bgcs.csv | Summary of 5'UTRs for genes in *A. nidulans* BGCs |
| PAM_per_gene_CDS.svg | Total Cas9/Cas12a PAM sites per gene in all genes/genes in BGCs |
| 5UTR_length_distribution.svg | Distribution of 5'UTR lengths in all genes/genes in BGCs |
| clusters.csv | Predicted BGCs, adapted from *A. nidulans* [portal on JGI](https://mycocosm.jgi.doe.gov/pages/sm-clusters.jsf?organism=Aspnid1&genomes=Aspnid1&clusterTypes=DMAT%2CHYBRID%2CNRPS%2CNRPS-Like%2CPKS%2CPKS-Like%2CTC&pageSize=50) |

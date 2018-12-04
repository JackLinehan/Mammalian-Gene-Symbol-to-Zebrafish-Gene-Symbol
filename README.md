# Mammalian-Gene-Symbol-to-Zebrafish-Gene-Symbol
These programs prepare user defined gene-set databases that can be used to run a Gene Set Enrichment Analysis. 
They take gene collections form MSigDB and returns orthologs and paralogs in the zebrafish. 
Use to prepare gene sets for Gene Set Enrichment Analysis using GSEA. 

These programs read in gmt files containg collections of gene sets from the Molecular Signatures DataBase. They assume that 
the genes in the collection are written as mammalian gene symbols. The programs breaks up the file from MSigDB into individual gene sets
and then reads in each individual gene in that set. It then uses biomaRt and mygene to find the correspondng genes in the zebrafish. 



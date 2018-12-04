# Mammalian-Gene-Symbol-to-Zebrafish-Gene-Symbol
These programs prepare user defined gene-set databases that can be used to run a Gene Set Enrichment Analysis. 

The programs read in gmt files containg collections of gene sets from the Molecular Signatures DataBase. They assume that 
the genes in the collection are written as mammalian gene symbols. The programs breaks up the file from MSigDB into individual gene sets and then reads in each individual gene in that set. It then uses biomaRt and mygene to find the correspondng genes in the zebrafish. 

Both programs return excel files as outputs. The excel files are organized so that each gene set occupies its own row. GSEA requires that each gene occupy its own column. One can manually flip rows to columns in excel. 

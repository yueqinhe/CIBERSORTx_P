# CIBERSORTx_P
This file is used to explain the operation of deleting some single-cell data in single-cell analysisis. We delect cells with:
1. low feature numbers (less than 250) or low UMInumbers (less than 500) (Cell debris or contents of broken cells)
2. low number of genes detected per UMI (log10GenesPerUMI < 0.8) (cells with low complexity, like red cells, which is one kind of cell contamination during biopsy taking)
3. high percentage of mitochondrial features (more than 20%) (drops with dead cells and croken cells which lost most of the gene, but still includ mitochondria).

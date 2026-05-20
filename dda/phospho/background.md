### Experimental context
The human phosphorylation datasets consist of 47 samples from condition A and 43 
from condition B. Two aliquots were processed for each sample: one dedicated to 
total proteome analysis and the other one to the phosphoproteome analysis. The 
main sample preparation steps were identical for proteomics and 
phosphoproteomics apart from the additional phosphopeptide enrichment step. 
Generated raw data files were searched against a database containing all human 
entries extracted from UniProtKB-SwissProt (25/08/2021, 20,339 entries) using 
MaxQuant (v.1.6.17). The minimal peptide length required was seven amino acids 
and a maximum of one missed cleavage was allowed. The mass tolerance for the 
precursor ions was set to 20 ppm for the first search and 4.5 ppm for the main 
search. The mass tolerance for the fragment ions was set to 20 ppm. For 
proteomics data, methionine oxidation and acetylation of proteins’ N-termini 
were set as variable modifications and cysteine carbamidomethylation as a fixed 
modification. For phosphoproteomics data, serine, threonine, and tyrosine 
phosphorylations were added as variable modifications. For protein 
quantification, the “match between runs” option was enabled. The maximum FDR 
was set to 1% at peptide and protein levels with the use of a decoy strategy. 
Intensities were extracted from the Evidence.txt file to perform the following 
statistical analysis. The dataset can be found on PRIDE (PXD043476).

### Data Source

The data of the full study were analyzed by Demeulemeester et al. (2025).

### References

Demeulemeester, N., Gébelin, M., Caldi Gomes, L., Lingor, P., Carapito, C., 
Martens, L., & Clement, L. (2024). msqrob2PTM: Differential Abundance and 
Differential Usage Analysis of MS-Based Proteomics Data at the Posttranslational 
Modification and Peptidoform Level. Molecular & Cellular Proteomics, 23(2), 
100708. https://doi.org/10.1016/j.mcpro.2023.100708
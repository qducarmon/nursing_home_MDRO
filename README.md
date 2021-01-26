# MDROs in a nursing home

This study investigated multi-drug resistant organism (MDRO) prevalence, spread and the relation of the gut microbiota with MDROs in a single Dutch nursing home. We have combined a number of analyses, namely clinical risk factor analysis for MDRO colonisation (GEE logistic regression), WGS for characterising MDRO isolates, 16S rRNA gene amplicon sequencing analysis to relate the microbiota to MDRO colonisation and on a subset of samples we performed metagenomic analyses to further investigate our unexpected findings regarding high *Bifidobacterium* relative abundance.
A link to the paper will be shared here upon publication.

## Requirements
- R version 3.6.1 ("Action of the Toes").
- All packages and dependencies loaded in the different markdown scripts.
- Download the data files from the data folder.
## Workflow
- In case you want to reproduce our analyses/figures, please first load the code/files in the Analysis_files_preperation.Rmd markdown file. This contains files for epidemiological, 16S analysis and metagenomic analysis. The only data not included in this file is for the *E. coli* isolate WGS analysis (these data/scripts are included in the AMR_WGS_Isolates.Rmd and Pangenomes.Rmd) and the *B. longum* strain comparisons (these can be found in the Bifido_strain_comparisons.Rmd markmdown).
- The easiest way to reproduce quickly is to make an Rproject with all scripts and data files, and then everything should run smoothly without having to change paths, etc. 
- The markdown files have been named according to the type of analysis, so if you are specifically interested in 1 analysis, you can check the respective files.
- The metalonda analyses take some time on a standard machine with 1000 permutations, keep that in mind. As for all other analyses, we also provide the results table for metalonda analyses, so this can be used directly to make the final figure.

## Contact
In case you have any questions about the code/analyses, you can contact me, [Quinten Ducarmon](mailto:q.r.ducarmon@lumc.nl)!
This directory contains tables for the analysis of gRNA specificity
in published CRISPR mouse and human screens. The tables are:

- `gene_scores.csv`: A table of published gene level scores from CRISPRi/a/ko screens in human 
                     and mouse as provided by the referenced publications. 
- `grna_scores.csv`: A table of published gRNA level scores from CRISPRi/a/ko screens in human 
                     and mouse as provided by the referenced publications.
- `human_grnas.csv`: A table of published human gRNAs and their Guidescan2 specificity scores
                     and number of off-targets at different distance thresholds. Guides with 
                     no exact matches in the human genome are also included and null values for 
                     the columns `chr,pos,strand,gene`.
- `mouse_grnas.csv`: A table of published mouse gRNAs and their Guidescan2 specificity scores
                     and number of off-targets at different distance thresholds. Guides with 
                     no exact matches in the mouse genome are also included and null values for 
                     the columns `chr,pos,strand,gene`.

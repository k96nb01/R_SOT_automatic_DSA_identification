# R_SOT_automatic_DSA_identification
Automatic DSA identification by comparing donor typing and Luminex single antigen bead results.

Version 1.1 is the initial version.

This code first calculates donor mismatches by comparing recipient and donor typing. The donor mismatches are then modified to match the format of the Luminex single antigen bead (SAB) results. The mismatches are then compared to the SAB results to find donor-specific antibodies with MFI values > 1,000. 

Note this code takes all SAB results as valid, and does not filter for results with high background, or results with reactivity to denatured epitopes. See other repositories for code that finds DSA based on manual analysis of clinical results, by searching report comments. 

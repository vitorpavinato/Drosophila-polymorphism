# Drosophila-polymorphism

Here's the corrected and more readable version:

This repository archives the Drosophila melanogaster polymorphism data and code used in Verdonk et al. 2024.

The analyses presented in the paper use only SNPs annotated as causing synonymous amino acid changes. All steps, from the acquisition of the original *D. melanogaster* data from the Zambia (DPGP3) population up to the annotation, can be found in the [Dmel_data](https://github.com/vitorpavinato/dmel_data) repository.

This repository contains the steps and code starting from the functional SNPs.

## data
Contains a .tsv file with only exonic SNPs for the four major D. melanogaster chromosomes.

## notebook
Contains a Jupyter notebook showing how to keep only synonymous and non-synonymous SNPs and associated gene information.

## src
Contains the code used to:
- Obtain the frequency (or density) of each codon pair;
- Correlate with codon change rates;
- Produce the plots.
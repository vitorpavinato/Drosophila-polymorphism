# Drosophila-polymorphism

Here's the corrected and more readable version:

This repository archives the *Drosophila melanogaster* polymorphism data used in Verdonk et al. 2024.

To obtain the `.tsv` file containing all SNPs, you should follow the [Dmel_data](https://github.com/vitorpavinato/dmel_data) repository. In this repository, [remake_vcf](https://github.com/vitorpavinato/dmel_data/tree/main/remake_vcf) describes the process of acquiring the original population-level multiple-sequence alignment data archived at [Drosophila Genome Nexus](https://www.johnpool.net/genomes.html) and transforming them to usable `.vcf` files. With a `.vcf` file in hand, we can annotate the variants with any pipeline. [annotate_vcf](https://github.com/vitorpavinato/dmel_data/tree/main/annotate_vcf) describes the annotation using SNPEff.

DGN contains an archive of all past population-level data published for this species. Here, we used only the samples from Zambia deposited as DPGP3.

## data
Contains a `.tsv` file with only exonic SNPs for the four major *D. melanogaster* chromosomes.

## src
Contains the code used to obtain the frequency (or density) of each codon pair, to correlate with codon change rates, and to produce the plots.
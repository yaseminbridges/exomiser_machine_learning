This directory contains the test corpora used in the Exomiser Machine learning experiments.

The code used to select the variants and the diseases for the neutral and pathogenic variants can be found in the `select_variants` notebook. Pathogenic/Likely Pathogenic variants were filtered from the clinvar VCF, neutral variants were selected from the gnomAD vcf on the condition they had an allele frequency of 0.02 & PASS filter - all variants appearing in the clinvar VCF were also filtered from the gnomAD VCF.


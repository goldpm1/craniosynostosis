# Craniosynostosis_WGS
- Whole-genome sequencing of 36 trios and 7 unrelated individuals of Craniosynostosis cohort (2024)
- Germline variant analysis
- Provides vcf, maf, or txt file (For bam files, we're trying to upload them in SRA)

## Overview of Craniosynostosis_WGS analysis

![CRS_figure_240502_01 Variant_pipeline](https://github.com/goldpm1/craniosynostosis/assets/62455201/9d0ce648-053d-4bff-a805-53cfa9620f62)

## Text files
### 01.denovo_shortvariant
- Octopus + Strelka + GATK haplotype caller
- De novo calls for 36 trios
### 02.unrelated_shortvariant
- Octopus + GATK haplotypecaller
- Short variant analysis for 7 unrelated trios
### 04.CNA_SV
- CNA or SV call using multiple caller
- Divided by target bin

# ANNOVAR-PCGR-integration
Identifying true single-nucleotide variations (SNVs) requires strict filtering steps. ANNOVAR-PCGR integration provides a comprehensive platform to identify true mutations with both cancer-related and general annotations. It also adds the copy number ratio of the mutated genes using the CVNkit tool outputs.

ANNOVAR-PCGR integration is a Python-based pipeline. It requires the output files of ANNOVAR (VCF file, bcftools can be used to filter non-functional mutations and those with high variant frequency among the general population), PCGR (TSV file), and CNVkit (CNS file). A list of  gnomad artifact mutations is added to the pipeline to flag mutations that were not passed gnomad filtering criteria.


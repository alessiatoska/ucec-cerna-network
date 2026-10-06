# data/

1. Save the GDC sample sheet here as `gdc_sample_sheet.tsv`.
2. Run `bash scripts/download_tcga.sh` from the project root.

Expected layout:

```
data/
├── gdc_sample_sheet.tsv
└── tcga_ucec/
    ├── <file-id>/<...>.rna_seq.augmented_star_gene_counts.tsv
    └── <file-id>/<...>.mirbase21.mirnas.quantification.txt
```

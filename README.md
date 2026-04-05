# Genome Assembly Project — VGP Galaxy Tutorial

## Project Overview
This repository contains the results and summary outputs from a genome assembly 
pipeline completed as part of a Bioinformatics course assignment. The workflow 
follows the Vertebrate Genomes Project (VGP) assembly tutorial on Galaxy.

## Tools Used
- **GenomeScope 2.0** — Genome size and heterozygosity estimation from k-mer analysis
- **BUSCO** — Assembly completeness evaluation using conserved single-copy orthologs
- **Hi-C scaffolding** (Salsa2 / 3D-DNA) — Chromosome-scale scaffolding using Hi-C data
- **Bionano Solve** — Optical genome mapping for structural validation
- **Merqury** — Reference-free quality value (QV) and completeness assessment

## Folder Structure
```
genome-assembly-project/
├── assembly-stats/      # Assembly statistics and Quast reports
├── busco/               # BUSCO completeness summaries and plots
├── genome-scope/        # GenomeScope k-mer plots and model output
├── hi-c-scaffolding/    # Hi-C scaffolding summary outputs
├── bionano/             # Bionano hybrid scaffold reports
├── merqury/             # Merqury QV scores and completeness plots
└── README.md            # This file
```

## File Selection Notes
Only summary files, statistics, and plots have been included in this repository.
Raw sequencing data (FASTQ), alignment files (BAM), and large intermediate 
files have been excluded due to GitHub file size limits (max 100 MB per file).

## Author
- **Name:** [Your Name]
- **Student ID:** [Your ID]
- **Course:** [Your Course Name]
- **Date:** [Date]
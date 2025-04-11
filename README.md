# Cancer RNA-seq Analysis with Nextflow + DESeq2

This project analyzes RNA-seq data from TCGA using a reproducible Nextflow pipeline and R (DESeq2). It performs:

- Quality control (FastQC)
- Trimming (TrimGalore)
- Alignment (STAR or HISAT2)
- Gene counting (featureCounts)
- Differential expression (DESeq2)
- Visualization (heatmap, volcano, PCA)

## Technologies Used

- Nextflow
- Docker
- R + DESeq2 + ggplot2
- TCGA-BRCA data

## Getting Started

### Prerequisites
- Install [Nextflow](https://www.nextflow.io/)
- Install [Docker](https://docs.docker.com/get-docker/) or Conda

### Run the pipeline
```bash
nextflow run main.nf -profile docker


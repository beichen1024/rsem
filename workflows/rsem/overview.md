# RSEM

RSEM is a software package for estimating gene and isoform expression levels from RNA-Seq data. It has support for multi-threaded computation, can run on single-end and paired-end data and may produce statistic values in support of it's expression analysis. For visualization, It can generate BAM and Wiggle files in both transcript-coordinate and genomic-coordinate. For visualization, user may use RSEM-made bam and wiggle files with UCSC Genome browser or IGV browser from Broad Institute. RSEM can also make transcript read depth plots in pdf format. For this workflow, only limited subset of RSEM toolkit is used. This workflow provides a building block for RNAseq data analysis pipelines.

![rsem flowchart](docs/RSEM_specs.png)

# rsem

RSEM 2.0, workflow for accurate quantification of gene and isoform expression from RNA-Seq data

## Overview

## Dependencies

* [rsem 1.3.3](https://github.com/deweylab/RSEM)


## Usage

### Cromwell
```
java -jar cromwell.jar run rsem.wdl --inputs inputs.json
```

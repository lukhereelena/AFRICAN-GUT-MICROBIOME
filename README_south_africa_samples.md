# South African Gut Metagenome Samples

## Overview
10 shotgun metagenomic samples from South Africa (PRJNA678454) processed through the same pipeline as Mozambique samples.

## Samples
| Sample ID | Location | Cohort |
|-----------|----------|--------|
| SRR17048881 | South Africa | — |
| SRR17048885 | South Africa | — |
| SRR17048888 | South Africa | — |
| SRR17048932 | South Africa | — |
| SRR17048935 | South Africa | — |
| SRR17048938 | South Africa | — |
| SRR17048941 | South Africa | — |
| SRR17048944 | South Africa | — |
| SRR17048947 | South Africa | — |
| SRR17048950 | South Africa | — |

## Processing Steps Completed
1. Raw data downloaded from ENA (fastq-dl)
2. FastQC quality control
3. Fastp adapter trimming and quality filtering

## Processing Steps Pending
1. MultiQC aggregation
2. Host read removal (Bowtie2)
3. Submission to Nephele for functional profiling

## Commands Used
See `south_africa_commands.txt`

## Date
June 16, 2026

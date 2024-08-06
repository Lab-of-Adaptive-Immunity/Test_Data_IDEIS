This repository contains analyzed data  of PBMCs of a Healthy Donor obtained from 10X Genomics page (<https://www.10xgenomics.com/datasets/pbm-cs-of-a-healthy-donor-5-gene-expression-and-cell-surface-protein-1-standard-3-0-0>) that can be used as small test for IDEIS software.

## LICENSE

The original data belong to 10X Genomics and are licenced under Creative Commons Attribution License (see the page above). The LICENCE file specifies the details. The provided RDS file and whitelist were generated from these data while BAM file is direct except from BAM file provided on above page.

## Details

The RDS file was generated from PBMCs of a Healthy Donor using 5' sequencing and includes a panel of TotalSeq antibodies. The main purpose of software is to test PTPRC detection with various software. To limit the size of file, the RDS file contains only UMAP projection and Antibody assay and BAM file was restricted to reads from Chromosome 1 within range of 195.000.000 - 200.000.000 bases. The whitelist contains the list of all cells present in RDS.

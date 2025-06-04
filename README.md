# Variant Calling Analysis

## Directory strucutre
<pre>```
└── Analysis
    ├── assemblies
    ├── fastq
    ├── genomes
    │   ├── annotated
    │   │   ├── PA14.csv
    │   │   ├── PA14.gff3
    │   │   └── PAO1.csv
    │   └── indexed
    └── variant_calling
        ├── annotated
        ├── curated
        │   ├── information
        ├── indels
        │   ├── annotated
        │   ├── information
        ├── raw
        ├── results
        ├── snps
        ├── totalpileup
        └── vcf```</pre>

## Softwares

For the code to work, the following must be installed:

- Conda
- Picard v3.4.0-0
- SAMtools v0.1.16
- Bowtie2 v2.5.4
- GATK v3.4-46
- Java8
- Java21
- SnpEff v5.2
- SnpSift v5.2
- Perl v5.32.1
- Annovar
- SPAdes
- Python 3.9 or higher
- pandas
- ipywidgets
- requests
- JupyterLab

## Installation

Some of these programs can be installed from the environment.yml file using the followinf command:

conda env create -f environment.yml

## Other considerations

The paths to the different programs must be correctly specified in the code, and the files PAO1.csv, PA14.csv, and PA14.gff3 must be located in the correct directory (./genomes/annotated/ directory).

Sample names must not contain underscores (_).

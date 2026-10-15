## Project Purpose

This project is a replication of Figures 5B, 5C, and 5D of this paper:
https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1012122#sec009

It is also for utilizing publicly available sequencing data for independent analysis.

Genome alignment and dataset generation done on Linux. Used Terminal on Mac.
Figure generation on R. Used Rstudio.

## Raw Data

These are links to the raw FASTA and FASTQ files.

Borrelia Burgdorferi CA-11.2A Reference Genome. Download the FASTA file. You may need to unzip the download.
https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000172315.2/

Raw Nanopore Long Reads Data. Three replicates. Download the FASTQ files.
https://trace.ncbi.nlm.nih.gov/Traces/?run=SRR27421011 #Replicate 1
https://trace.ncbi.nlm.nih.gov/Traces/?run=SRR27421012 #Replicate 2
https://trace.ncbi.nlm.nih.gov/Traces/?run=SRR27421013 #Replicate 3

## Workflow

If one wants to replicate the work here or use it as a frame of reference for their own genome alignment and figure generation project,
please peruse the documents in this order. It's best to locate the raw data independently as well as an exercise.

1. seqpipe.sh 
Commands for genome alignment and dataframe generation.
I provided the raw tsv's if you want to skip this alignment step or visualize it.
Includes filtering commands as well.

2. BB1Fig5BCD.Rmd for commands on R or BB1Fig5BCD.pdf if you only want the output.
Generation of figures from dataframes. Comments included within file.

3. BB1 Presentation.pptx 
Presented on 2/10/26

4. phiBB1_figure_analysis_essay.pdf 
An analysis of the original publication and an explanation of their methods. 
Includes figure analysis with comparisons between the original and the reconstruction. Completed on 5/26/26.

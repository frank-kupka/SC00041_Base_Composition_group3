## Purpose
This tiny script takes a fasta file and displays base counts for the first sequence in it. 

## Instructions for Running Code

### Install dependencies

This script requires R and the following R packages:
 ```
'Biostrings, ggplot2
 ```

You can create a Conda environment with all the dependencies installed by running:
 ```
 conda env create -f environment.yml
 ```

### Run the script
Your input data must be named 'fasta.fa' and stored in the 'data' directory next to the script;
To execute the sript run
 ```
Rscript base_composition.R
 ```

## What output to expect
A .PNG file with base counts rendered as a bar plot.

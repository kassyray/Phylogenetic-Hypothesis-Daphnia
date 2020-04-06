# Phylogenetic-Hypothesis-Daphnia
This pipeline constructs a phylogeny from the 16S gene records of Daphnia collected from the NCBI database

A pipeline that:
- collects 16S data from NCBI
- cleans, reformats, pre-processes data 
- filters data
- performs a multiple sequence alignment (MSA) 
- clusters sequences into OTUs (Operational Taxonomic Units) 
- visualizes results 
- assesses visualization for outliers
- reconstructs phylogenetic relationships 

Dependencies: 

R 

- library(rentrez)
- library(seqinr)
- library(Biostrings)
- library(stringr)
- library(tidyverse)
- library(ggplot2)
- library(stringi)
- library(ape)
- library(DECIPHER)

This project was completed for University of Guelph's BINF 6210 course (Software Tools for Biological Data Analysis and Organization) 

Author: Kassy Raymond 

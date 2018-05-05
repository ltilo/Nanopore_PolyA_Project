# Nanopore_PolyA_Project

### prepare.R
In my first step I focus on learning how to load up information from fast5
files and plotting this. The rhdf5 library can also be used to manipulate
the fast5 files. In this file you can see what I did to show the example data.

### using_poretools_and_minimap2_and_samtools.sh
In this file you can see my steps how to create the *.bam file from the raw
data. I used poretools, minimap2 aligner and samtools.

### main.R
This is my main R-script using all the function and plotting the result

### read_plot_functions.R
This file contains all read functions, plot functions and also some logic
functions used by main.R

### findPolyA.cpp
In this file you can find all function I wrote to find the ployA using rcpp.

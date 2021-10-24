## nucleotide_statistics_from_fasta.py
This python program takes in a file and calculates the number of times the bases A,T,C,G and N occur in the sequence and also calculates the GC% in addition to the length of the sequence.
## Description
The program which will open this file and generate two files. One which is the protein sequence (pdb_protein.fasta), and the other which is the secondary structures (pdb_ss.fasta). 
get_fh() gets the file handle to sequences in the fasta file, get_header_and_sequence_lists() stores the header and sequences in two seperate lists, and _get_nt_occurence() calculates the occurences of the bases, _get_accession() returns the accession number of the header line and print_sequence_stats() prints the statistics into the output file.
## Getting started

## Dependencies

Runs on linux or any other CLI

## Installing

The programs can be found on the programming6200/assignment3 directory on defiance

## Executing programs

$ python3 nucleotide_statistics_from_fasta.py --infile influenza.fasta --outfile influenza.stats.txt
$ python3 nucleotide_statistics_from_fasta.py -h
$ python3 nucleotide_statistics_from_fasta.py 
$ python3 nucleotide_statistics_from_fasta.py --infile influenza.fasta

## Author
Amoolya Srinivasa

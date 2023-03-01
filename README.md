# SPADES_fastafilter
Filters fasta sequences of contigs based on length and coverage (optional)

After assembling multiple genomes using SPAdes, a fasta file containing the contigs sequences and a tabular file containing the contig length and coverage would be generated for each genome assembly. As filtering contigs based on length and coverage for multiple genome assemblies is a time consuming task, with the help of the program spades_fastafilter.py this task can be completed quicker.

### Input:

Among the SPAdes results generated, the fasta files containing contig sequences and the tabular files containing the length and coverage of the contig sequences should be downloaded as two separate zip folders. The zip folders should be extracted and given as input.

### Pre-requirements:

Python

csv

pathlib

argparse

glob

os

SeqIO


### Usage:

`python spades_fastafilter.py -ffol <fasta folder location> -tfol <tabular folder location> -l <length> [-c <coverage>]` 

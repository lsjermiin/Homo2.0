NAME
Homo

VERSION
2.0

COPYRIGHT
Copyright © 2019 Lars Sommer Jermiin. All rights reserved.

WARNING
The copyright holder takes no legal responsibility for the correctness of results obtained using this program.

AUTHOR
Lars Sommer Jermiin

ADDRESS     Australian National University
            University College Dublin            

CONTACT     lars.jermiin@anu.edu.au
            lars.jermiin@ucd.ie

DATE        18 August 2019

PURPOSE     Homo conducts the matched-pairs test of symmetry for pairs of sequences of
            nucleotides, di-nucleotides, codons, genotypes and amino acids.
            
            Homo also computes thre types of compositional distances between these pairs
            of sequences (including a compositional distance and the Euclidean distance)
 
FORMAT      Sequences must be stored in the FASTA format.
 
DATA TYPES  Sequences can be read a strings of one, two, or three nucleotides, strings 
            of 10- or 14-state genotypes, or as strings of amino acids.

COMPILE     g++ homo_2.0.cpp -o homo -O3 -Wall -lm

HELP        Simply type homo in the command line

STATUS      Software complete

NOTE        Contact author for updates, etc

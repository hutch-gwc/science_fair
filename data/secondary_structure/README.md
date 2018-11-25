# DMS data
SKH

In this directory I have added 2 deep mutational scanning datasets and 3 codon-level alignments for the influenza virus surface protein hemagglutinin (HA).

## Deep Mutational Scanning  

I have included two deep mutational scanning sets: [`H1_dms.csv`](H1_dms.csv) and [`H3_dms.csv`](H3_dms.csv).
Both are deep mutational scans for the influenza virus surface protein HA.
One is done on the H1 variant of HA and one is done on the H3 variant of HA.
H1 and H3 are two variants which are diverged (only 42% identical on the amino-acid level) but perform the same function and infect humans every year (seasonal H1N1 and seasonal H3N2, respectively).

Each file is a comma-separated file with 21 columns.
The first column is the site and the next 20 columns are the 20 amino-acids.
Therefore, you will have one dms "preference" measurement for each of the 20 amino acids at each site in the protein.

## Alignments

I have included 3 alignment files containing HA sequences.
There is an alignment of just H1 sequences ([`H1_seqs.fasta`](H1_seqs.fasta)), an alignment of just H3 sequences ([`H3_seqs.fasta`](H3_seqs.fasta)) and an alignment of all 15 HA subtypes, including H1 and H3 ([`HA_seqs.fasa`](HA_seqs.fasta)).

All of the files are in the fasta format.

## Note on numbering

The data in this directory are already aligned and only contain homologous sites of HA.
That is site 1 in the H1 data is equivalent to site 1 in the H3 data.
This is true of the preference sets and the alignments. 

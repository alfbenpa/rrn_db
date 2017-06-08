# rrn_db

This repository contains information related with the publication entitled: Benítez-Páez A, Sanz Y. Multi-locus and long amplicon sequencing approach to study microbial diversity at species level using MinION(TM) portable nanopore sequencer. GigaScience 2017.


File description:

1) operon.100.fa.tar.gz, contains the sequence database of rrn operons used for read mapping.

2) species_annotation, is a tab-delimited text file containing the annotation of every single rrn operon in the database. Column information = bacterial species, operon identifier, GenBank identifier, operon length (bp).

3) D6305.random.fasta & HM782D.random.fasta, are a normalized subset of 10,000 sequences per sample created by random selection after shuffling (10,000X) of the original dataset.

4) amplicon5k.bc[1/8].[F/R].fasta files, are the fasta files of the filtered+split reads obtained during MinION sequencing of amplicons generated from HM782D and D6305, respectively.

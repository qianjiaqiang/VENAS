# VENUS：a Viral genome Evolution Network Analysis System

## Introduction

  Comprehensive analyses of viral genomes can provide a global picture on SARS-CoV-2 transmission and help to predict the oncoming trends of pandemic. However, the rapid accumulation of SARS-CoV-2 genomes presents an unprecedented data size and complexity that has exceeded the capacity of existing methods in constructing evolution network through virus genotyping. The VENAS seeks to apply reliable computational algorithms to build an integrative genomic analysis system that enables researchers to trace viral mutations along the transmission routes using the daily updated SARS-CoV-2 genomes.

  VENUS uses Hamming distances adjusted by the minor allele frequency to construct viral genome evolution network. The resulting network was topologically clustered and divided using community detection algorithm, and potential evolution paths were further inferred with a network disassortativity trimming algorithm. VENAS can construct the network from 14,949 sequences in about 10 minutes.

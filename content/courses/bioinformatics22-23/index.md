---
title: Bioinformatics course 2022/23
summary: The complexity and amount of biomolecular and genomic data available today requires the use of computational methods both for their management and above all for the extraction of biological and functional information. Bioinformatics is the discipline that deals with the analysis and attribution of biological meaning to the amount of molecular data available to date and represents an essential tool in the field of biochemical, biological-molecular, biomedical and biotechnological activities.
tags:
  - Bioinformatics
  - E-health
date: '2022-11-16T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
url_code: '' # change to github
url_pdf: ''
url_slides: 'https://www.ncbi.nlm.nih.gov/books/NBK569562/'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

• Week 1: 

**Introduction to bioinformatics course**

This lesson illustrates the scientific field in which Bioinformatics operates. The term "Bioinformatics" today is difficult to define because it now encompasses many different activities. Our course will deal with the most "classical" part of bioinformatics and will try to give the basic concepts on which everyone can build their growth and sectoral knowledge.

-> Tips for becoming a good computational biologist
-> A fun guide to becoming a bioinformatician

**Biological databases**

This lesson provides an overview of the databases available in the field of molecular biology. The databases are very numerous and this lesson will help the student to make some orders so as not to get lost in the labyrinths of the network.

-> Databases may contain errors!
-> Example of a file included in the EMBL / ENA database
-> Expasy - The portal of the Swiss Institute of Bioinformatics through which you can access many interesting and useful resources on the Internet.
-> UniProt - UniProt database portal.
-> Protein Data Bank - Portal of the Protein Data Bank, the bank containing the atomic coordinates of proteins and nucleic acids.
-> NCBI - National Center for Biotechnology Information Portal. A portal that allows access to various resources including the PubMed database, GenBank, RefSeq and many others.

Week 2:

**Alignment of two sequences**

This lesson illustrates the basic methods most commonly used to compare amino acid or nucleotide sequences.

-> EMBOSS Tools at EBI - This link takes you to the European Bioinformatics Institute website page containing several sequence analysis programs of the EMBOSS package
-> Comparison of genomes
-> Points of Significance: Significance, P-values, and T-tests
-> Highlights: The Importance of Being Uncertain
-> What is dynamic programming?

Week 3:

**Scoring matrices**

This lesson introduces scoring matrices used to align or compare protein sequences. The meaning of the points contained in the matrix cells is clarified by examining the logic underlying their calculation.

**Database searches**

This lesson describes the main sequence database search programs, such as FASTA and BLAST. After reviewing the problems inherent in rapidly searching for sequence similarities in databases of increasing size, technical solutions that have been proposed by various authors are illustrated. Some suggestions are also given for frontier developments in the genomic era.

-> Using BLAST
-> BlastX and TblastN
-> FASTA - The University of Virginia portal for accessing the FASTA program and its various versions. There are other portals at other institutions, easily identifiable through a Google search. Note the GGSEARCH and SSSEARCH versions which use an exact algorithm (Needleman & Wunsch and Smith & Waterman respectively) instead of a heuristic algorithm like FASTA
-> FASTA and Blast in EBI
-> Blatt
-> caBLAST - compression-accelerated BLAST: a new tool for rapid and massive genomic searches. You can download the program code for local installation.


Week 4:

**Multiple alignments and PSSM**

Description of the most common methods of calculating multiple alignments. Computation of profiles (PSSM) and use for searching databases. Profile database searches.

-> Clustal Omega
-> MUSLCE
-> EMBOSS Web
-> Conserved Domain Database (CDD)
-> Jalview - Multiple alignment editor with many functions, including the ability to calculate multiple alignments, secondary structure predictions, calculation of cladograms, etc. .. It can be downloaded for free from the indicated address.
-> Phylogenetic analysis


Week 5:

**Hidden Markov Models (HMM)**

This lesson addresses the application of statistical methods in the analysis of biological sequences, addressing both their application in the context of techniques for predicting gene characteristic elements, as well as the representation of multiple alignments of correlated proteins to conduct research. in databases.

-> Simple introduction to HMM
-> Markov chains
-> HMMSEARCH
-> HMMER
-> PFam - Database of protein domain families encoded as HMM profiles
-> SMART
-> SuperFamily - Server that allows you to assign a protein sequence (or the translation of a nucleotide sequence) to a specific protein family with a known structure, where possible. Protein families are represented by HMM.
-> HHPred
-> TMHMM - Prediction of transmembrane helices with HMM
-> EMBOSS explorer - Web interface to the programs included in EMBOSS

**Prediction of structural features of proteins**
Learning about predicting different structural features of proteins based on sequence alone. We examine several algorithms capable of inferring correlations between sequence properties and various structural properties in proteins (secondary structure, solvent accessibility, proteolytic cleavage sites, protein-protein interaction sites).

-> Introduction to neural networks
-> Support Vector Machines (SVM)
-> SPPIDER - Site that provides protein-protein interaction predictions based on neural networks
-> NetMHC - Prediction of peptides that can potentially bind to MHC receptors


Week 6:

**Molecular graphics and comparison of protein structures**

-> Molecular graphics
-> Swiss-PdbViewer
-> Chimera
-> Visual Molecular Dynamics (VMD) - A molecular graphics program oriented towards the analysis of molecular dynamics trajectories, but equipped with many functions of more general use.
-> Free PyMOL
-> Open PyMOL
-> FatCat - Server for flexible protein aggregation
-> The server QUIT

**Fold recognition**
Identification of folds compatible with a given protein sequence.ù

-> Phyre2
-> GenThreader


Week 7:

**Molecular docking**

Molecular docking is a key tool in structural molecular biology and computer-aided drug design. The goal of ligand-protein binding is to predict the predominant mode(s) of binding of a ligand to a protein of known three-dimensional structure. Successful docking methods efficiently search high-dimensional spaces and use a scoring function that correctly ranks candidate dockings. Docking can be used to perform virtual screening of large compound libraries, rank the results, and propose structural hypotheses about how ligands inhibit the target, which is invaluable in lead optimization. Setting the input structures for docking is as important as the docking itself, and analyzing the results of stochastic search methods can sometimes be ambiguous. This chapter discusses the background and theory of molecular docking software and covers the use of some of the most commonly cited docking software.

Week 8:

**Homology modeling**

This lesson illustrates the theoretical and technical principles for constructing homology models.

-> SWISS-MODEL - Site for building homology models
-> QMEAN - Swiss-Model site where the validation method for structural models is available
-> Prosall - Structural model validation site

Week 9:

**Molecular mechanics**

Week 10:

**From protein structure to function**

-> ConSurf - Analysis of evolutionary conservation of protein residues
-> SPIDDER- Prediction of protein-protein interaction sites based on 3D structure
-> cons-PPISP - Prediction of protein-protein interaction sites based on 3D4 structure
-> DiscoType - Prediction of disrupted epitopes recognized by B cells based on 3D structure
-> BePRO - Prediction of interrupted epitopes recognized by B cells based on 3D structure
-> DUET - Predicting the effect of point mutations on the stability of a protein
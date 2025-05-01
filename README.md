# ASB_1-assignments
This repository contains the code, data, and detailed steps for reproducing the rodent phylogeny analysis as performed in the selected research paper. The objective of this project is to reproduce the original phylogenetic tree construction using molecular data from rodent species, following the methods outlined in the referenced study. 
# Brief description
This script works with the combine effort of all teams and also with the use of our individual knowledge to understand, analyse and observe the phylogetic relationships among Rodents.We made our observation from a giving article which is " Rodent phylogeny revised: analysis of six nuclear genes from all major rodent clades Shani Blanga-Kanfi1, Hector Miranda2,4, Osnat Penn3, TalPupko3, Ronald W DeBry2 and Dorothée Huchon*1 ". This article contains all the giving procedure to determine and advance on our reseach. It contains 6 nuclear genes, accession number of all gene and also a perfect analysis on our research which involues phylogenetics. The genes used where adra2b.gene,CB1.gene,vWF.gene,GHR.gene,RAG2.gene,IRBP.gene.the genes where concatenated to bring out a single analytical gene,which means all 6 genes was placed into a single gene. In other to get a phylogenetic tree we followed some software commands/principles like Maftt, Python,concatenation of gene, Biopython ,........The purpose of these commands is to align genes of arranging sequences of DNA, RNA, or proteins to identify regions of similarity that may be a consequence of functional, structural, or evolutionary relationships between the sequences but in this case we used DNA and slso we used script is to automatically retrieve nucleotide sequences for specific nuclear genes from GenBank using their unique accession numbers. These accession numbers were collected from the article and stored in NCBI (National Center for Biotechnology Information) for extraction and verification. These sequences are intended for use in the phylogenetic analysis of rodent species.  We also used a python script to change Fasta to Nexus file , which we did to get Bayesian interference analyses(which determines the statistical inferences in which the statistician assigns subjective probabilities to the distributions that could generate the data. These subjective probabilities form the so-called prior distribution.) Biopython Library: Used to handle sequence data retrieval from GenBank. Data Input: A list of GenBank accession numbers corresponding to the genes studied) and Output Format: FASTA format (standard format for storing nucleotide sequences).

# Installation instructions
MrBayes is a program for Bayesian inference and model choice across a wide range of phylogenetic and evolutionary models. MrBayes uses Markov chain Monte Carlo (MCMC) methods to estimate the posterior distribution of model parameters.
A good resource for new users is the MrBayes 3.2 manual, which contains instructions for downloading and installing the program, two tutorials including a quick-start version, discussions of all the models implemented in the program, answers to some frequently asked questions, and a list of the differences between versions 2 and 3 of the program. In an appendix, there is a diagrammatic summary of all the models implemented in the program and most of the proposal mechanisms. You can download the manual (pdf) here.

Online Help
MrBayes 3 provides extensive online help through the help command. Simply type help at the command prompt to get a list of the available commands. Type help <command> to get help information for a specific command. For instance, help lset will give you the help information for the lset command, including a discussion of all the available parameters and options. The help information for a command typically also includes a summary table of the options and current settings.

Command Reference
You can produce a text file containing all the help information for the current version of the program by using the manual command in MrBayes. If you produce this file immediately after starting the program, the text file will contain all the default settings and can be used as a command reference.

General Advice
Remember that MrBayes is free software and that it currently has thousands of users around the world. Therefore, the authors have no possibility to provide extensive user help. Please first read the manual and the command reference carefully to make sure the problem you are having is not addressed there. If the problem you are having seems to be a bug in the program, report it as described here.

- For other systems, please make sure you have following packages/libraries installed:
- MAFFT
- BIOPYTHON
- 

# Objectives
based on our research and the tasks giving to make our reseach successful we followed the giving objectives :
- Reproduce phylogenetic analysis from the selected study.
  retreiving and collecting sequences from NCBI (National Center for Biotechnology Information) and using accession number to get the sequence . The accession numbers was gotten using 
  python,Biopython scripts.
- Align and trimmed nuclear gene sequences across multiple rodent clades.
  Using varios software like Maftt ......., we were able to align the genes and trimmed them.
- Build concatenated phylogenetic trees.
  python follows a concatenated process, In other words we concatenated the genes into a single gene file
- Changing fasta to Nexus
  We also used a python script to change Fasta to Nexus file , which we did to get Bayesian interference analyses(which determines the statistical inferences in which the statistician 
  assigns subjective probabilities to the distributions that could generate the data. These subjective probabilities form the so-called prior distribution.)
- Compare results with the original paper.
   ...........................................................
  #  SOFTWARE AND COMMANDS
  - Maftt
  - PYTHON 
  - BIOPYTHON
  - 

  # CREDITS
  Louis john Andrew idehen- 202300115
  Sara
  Maria
  Fabio 


  # References 

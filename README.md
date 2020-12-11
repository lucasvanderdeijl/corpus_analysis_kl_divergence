# Corpus Analysis with  Kullback–Leibler divergence

Author: Lucas van der Deijl, University of Amsterdam <br/>
Version: 9 December 2020 <br/>
Contact: l.a.vanderdeijl@uva.nl, www.lucasvanderdeijl.nl <br/>
Project: 'Radical Rumours' (Funded by NWO 2017-2021) <br/>

## Aim of this program
The program offers a basic method to analyse asymmetrical relationships between word type distributions in document pairs from either one corpus or two different corpora. Textual similarity is formalised as [KL divergence](https://en.wikipedia.org/wiki/Relative_entropy) based on [tf-idf values](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) for every word type in the corpus. The results are visualised as a boxplot or as a heatmap.

This Jupyter notebook can be used to reuse the code or to replicate the analysis with different corpora. Run each code block individually or use the 'Run all'-option from the Cell-tab.

## Pipeline

The pipeline desigend to achieve the program's aim performs the following steps:

+ Import the required libraries
+ Install missing libraries
+ Define functions for preprocessing and parsing
+ Load and preprocess your corpus
+ Create a term-document matrix with tfidf values
+ Create a document-document matrix and compute KL divergence for both directions in each document pair
+ Visualise the results as boxplots
+ Visualise the results as heatmap

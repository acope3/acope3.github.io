---
layout: paper
title: "Gene expression of functionally-related genes coevolves across fungal species: detecting coevolution of gene expression using phylogenetic comparative methods"
image: 
authors: Cope AL, O'Meara BC, Gilchrist MA.
year: 2020
ref: Cope et al. 2020. BMC Genomics
journal: "BMC Genomics 21(370)"
pdf: 
doi: https://doi.org/10.1186/s12864-020-6761-3
tags: expression
---

# Abstract

## Background
Researchers often measure changes in gene expression across conditions to better understand the shared functional roles and regulatory mechanisms of different genes. Analogous to this is comparing gene expression across species, which can improve our understanding of the evolutionary processes shaping the evolution of both individual genes and functional pathways. One area of interest is determining genes showing signals of coevolution, which can also indicate potential functional similarity, analogous to co-expression analysis often performed across conditions for a single species. However, as with any trait, comparing gene expression across species can be confounded by the non-independence of species due to shared ancestry, making standard hypothesis testing inappropriate.

## Results
We compared RNA-Seq data across 18 fungal species using a multivariate Brownian Motion phylogenetic comparative method (PCM), which allowed us to quantify coevolution between protein pairs while directly accounting for the shared ancestry of the species. Our work indicates proteins which physically-interact show stronger signals of coevolution than randomly-generated pairs. Interactions with stronger empirical and computational evidence also showing stronger signals of coevolution. We examined the effects of number of protein interactions and gene expression levels on coevolution, finding both factors are overall poor predictors of the strength of coevolution between a protein pair. Simulations further demonstrate the potential issues of analyzing gene expression coevolution without accounting for shared ancestry in a standard hypothesis testing framework. Furthermore, our simulations indicate the use of a randomly-generated null distribution as a means of determining statistical significance for detecting coevolving genes with phylogenetically-uncorrected correlations, as has previously been done, is less accurate than PCMs, although is a significant improvement over standard hypothesis testing. These methods are further improved by using a phylogenetically-corrected correlation metric.

## Conclusions
Our work highlights potential benefits of using PCMs to detect gene expression coevolution from high-throughput omics scale data. This framework can be built upon to investigate other evolutionary hypotheses, such as changes in transcription regulatory mechanisms across species.
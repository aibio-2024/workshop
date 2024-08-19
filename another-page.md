---
layout: default
title: Another page
description: This is just another page
---

## Abstracts


## Day 1 (August 26th), Morning Session


### Nick Generous      

TBD

### Carrie Manore       

TBD       

### Morgan Gorris       

TBD       

### Lauren VanDervort   

TBD

### Beth Stelle        

Some AI-driven biology research may be subject to federal regulations for human subjects research (HSR). We will provide an overview of what constitutes HSR, give examples of LANL HSR, and explain the review process.                   


## Day 1 (August 26th), Afternoon Session


### Sandrasegaram Gnanakaran   

TBD

### Bin Hu                     
Mutations in proteins directly impact their structure and function. Understanding the “language” of proteins, or the sequence to function (genotype-phenotype) relationship has many real-world applications. One set of applications includes those in biodefense, such as biological threat detection and biosurveillance, antibody engineering, and medical countermeasure development. In this study, we present a novel language model-based approach that can rapidly analyze vast collections of sequences, and make near real-time functional predictions that compare favorably to those made using conventional bioinformatic and experimental methods. Our findings reveal that tailored protein language models can predict protein mutation phenotypes, such as binding affinity or level of expression, when they are trained with high-throughput functional data. Protein language models applied to viral genomes can also discern the lineage within a family (e.g., sarbecovirus sequences). Coupled with sequenced-based biosurveillance, this type of model may provide early warning signals of potential zoonotic spillovers (i.e. host jumping) or “escape” from existing medical countermeasures posed by novel mutations. This research not only underscores the potential of ML and language models in addressing pressing challenges in understanding the mapping of sequence to function, but further elucidates their potential application in accelerating the response to biological threats as they evolve.

### Blake Hovde                

We are currently investigating the use of biologically trained LLMs for classifying large volumes of DNA sequencing data that has been annotated with protein and gene information, and trying to distill/summarize the information using LLMs for easy human digestion of the information.

### Jason Gans                

Accurate computational prediction of protein-protein binding affinities has the potential to significantly decrease the time and cost for designing proteins that can specifically bind to biologically relevant target proteins for detection, diagnostic and therapeutic applications. While recent advances in the field of de novo protein design offer the possibility of using computationally designed proteins as affinity reagents, current protein design methods do not predict the strength of protein-protein binding (e.g., the equilibrium binding constant Kd).

Quantitative computational prediction of protein-protein binding affinity is a challenging problem. Atom-level simulations of protein-protein binding are time consuming and resource intensive (typically requiring large computer clusters) due to the large number of protein and solvent degrees of freedom that must be computationally explored. Machine learning (ML) offers a potentially faster method for predicting protein-protein binding affinity by associating patterns in amino acid sequence and/or 3D protein structure with experimentally measured Kd values. However, ML-based prediction of protein-protein binding affinity is challenging due to (a) the limited amount of independent training data (due to the presence of homologous proteins in publicly available data), and (b) the large number of possible ways to computationally represent a pair of proteins in a ML algorithm (i.e., feature selection). Groups of similar proteins can confound naïve attempts to assess affinity prediction accuracy using cross validation by randomly partitioning closely related protein pairs into both training and testing sets (leading to overly optimistic estimates of prediction performance).

To account for similarity-induced biases in the available datasets of protein-protein binding affinity, the DTRA-funded BioRAD project has developed a cross validation framework that hierarchically clusters the available input data (consisting of 3D protein heterodimer structures and associated Kd values) by protein sequence similarity. At each level of this hierarchy, cross validation is performed on clusters of protein pairs (as opposed to individual protein pairs). This process provides an increasingly stringent evaluation of ML prediction methods and how accurately binding affinity predictions can generalize to protein pairs not previously encountered. Using this cross validation approach, different ML models were evaluated using experimental protein heterodimer 3D structures and associated Kd values collected from the open literature by the PDBBind database. The results demonstrate that the proposed cross validation framework can guide the selection of ML models that more accurately predict the binding affinity for previously unknown protein pairs.

### Michael Wall              

TBD



## Day 2 (August 27th), Morning Session


### Manish Bhattarai    

To ascertain the precise relationship between TF binding and DNA breathing, we developed the multi-modal deep learning model  EPBDxDNABERT-2, which is based on the Extended Peyrard-Bishop-Dauxois (EPBD) nonlinear DNA dynamics model. To train our EPBDxDNABERT-2, we used chromatin immunoprecipitation sequencing (ChIP-Seq) data  comprising 690 ChIP-seq experimental results encompassing 161 distinct TFs and 91 human cell types.  EPBDxDNABERT-2 significantly improves the prediction of over 660 TF-DNA, with an increase in the area under the receiver operating characteristic (AUROC) metric of up to 9.6% when compared to the baseline model that does not leverage DNA biophysical properties. We expanded our analysis to in vitro high-throughput Systematic Evolution of Ligands by Exponential enrichment (HT-SELEX) dataset of 215 TFs from 27 families, comparing EPBD with established frameworks. The integration of the DNA breathing features with DNABERT-2 foundational model, greatly enhanced TF binding predictions. Notably,  {EPBDxDNABERT-2, trained on a large-scale-multi-species genomes, with a cross-attention mechanism, improved predictive power shedding light on the mechanisms underlying disease-related non-coding variants discovered in genome-wide association studies. 

https://www.biorxiv.org/content/10.1101/2024.01.16.575935v2.abstract
https://github.com/lanl/EPBD-BERT 
      

### Juston Moore       

Bayesian optimization over the latent spaces of deep autoencoder models (DAEs)
has recently emerged as a promising new approach for optimizing challenging
black-box functions over structured, discrete, hard-to-enumerate search spaces
(e.g., molecules). Here the DAE dramatically simplifies the search space by map-
ping inputs into a continuous latent space where familiar Bayesian optimization
tools can be more readily applied. Despite this simplification, the latent space
typically remains high-dimensional. Thus, even with a well-suited latent space,
these approaches do not necessarily provide a complete solution, but may rather
shift the structured optimization problem to a high-dimensional one. In this paper,
we propose LOL-BO, which adapts the notion of trust regions explored in recent
work on high-dimensional Bayesian optimization to the structured setting. By refor-
mulating the encoder to function as both an encoder for the DAE globally and as a
deep kernel for the surrogate model within a trust region, we better align the notion
of local optimization in the latent space with local optimization in the input space.
LOL-BO achieves as much as 20 times improvement over state-of-the-art latent
space Bayesian optimization methods across six real-world benchmarks, demon-
strating that improvement in optimization strategies is as important as developing
better DAE models.

### Shounak Banerjee    Learning Growth Curves: Algae Crops vs Harmful Algae Blooms  

### Sayera Dhaubhadel   Suicide veteran predictions using transfer learning                                 


## Day 2 (August 27th), Afternoon Session


### Sara del Valle      

TBD   

### Casey Gibson        

TBD

### Yen Ting Lin       

TBD


### Ruian Ke           

Data science and machine learning approaches for identifying rapidly expanding SARS-CoV-2 lineages using genetic data - applying various data science/machine learning tools to analyze CoV-2 genetic sequencing data. 

### Qianying Lin        

Genomic reassortment is a complex procedure that allows viruses with genomic segments exchange genetic materials during co-infected in the same cell after a host is dually infected by distinct viruses, with potential to produce highly contagious new variants.
With its intrinsic genetic complexity, common phylogenetic and phylodynamic methods are no longer proper to infer the reassortment pattern and biological mechanism.
In this talk, we first present a simulator that simulates both the viral transmission among host population and the within-host viral evolution simultaneously when putting them in the context of a epidemiological model.
We further build a likelihood-free mapping between the epidemiological model of interest and the genomic data and use it for reassortment inference using typical neural network models.




[back](./)

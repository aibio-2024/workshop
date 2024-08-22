---
layout: default
title: Abstracts 
---




## Day 1 (August 26th), Morning Session


### Nick Generous    

#### AI and Biological Risk

The convergence of Artificial Intelligence (AI) with laboratory automation presents a dual use dilemma, wherein the same technologies can both significantly benefit scientific research but also pose potential misuse risks, especially for the development of biological threats. Three areas of concern emerge: 1. Frontier models that have the potential to synthesize information leading to the possibility of a “how-to guide” on WMDs; 2. AI-enabled biological design tools, which could potentially design novel biological agents; and 3. the integration of frontier models with biological design tools and autonomous laboratories, compounding the threat by potentially creating an automated AI-powered feedback loop. 
 
These technologies’ disruptive potential can profoundly impact national security. They lower the technical threshold for acquisition/development by proliferators and non-state actors, potentially facilitating the creation of sophisticated threat agents as well as pandemic-potential pathogens. Effective risk evaluation requires understanding not only the capabilities of AI models but also their broader implications in the military and security spheres. This necessitates the development of testbeds, evaluation tools, frameworks, and comprehensive assessment methodologies to enable rigorous and systematic evaluation of the risks associated with these computational and experimental technologies. These capabilities are crucial to inform AI governance efforts. This talk aims to equip the audience with a greater understanding of the risks posed by AI in the context of biological threats, to explore technical challenges, and to assess how these trends will impact the security environment.
 

### Carrie Manore       

#### Using a hybrid approach of AI and mechanistic models to predict climate change impact on infectious diseases       


### Morgan Gorris       

#### Projecting the geographical distribution of mosquitoes in response to climate change

The geographical ranges of mosquitoes, important disease vectors, are sensitive to both climate and land use conditions. Climate change may cause the geographical range of mosquitoes to expand, shift, or contract, ultimately changing what communities are at risk for contracting mosquito-borne diseases. We used a machine learning, ecological niche model and projections of climate and land use to project the geographical ranges of nine important mosquito species across North and South America through year 2100. In short, mosquito borne disease will continue to be a threat to human health. Our study is an example of how machine learning, a subset of AI, can be used in multidisciplinary science.
       

### Lauren VanDervort   

#### Statistical Bias and Predictive Modeling
In this talk, a LANL statistician shares their experiences and thoughts surrounding statistical bias in several real-world applications, including disease modeling using electronic health records data, risk prediction modeling for cancer patients, and infectious disease forecasting. This talk highlights biases related to data representativeness, measurement error, missing data, extrapolation, and reporting delay.
 

### Beth Stelle        

#### AI and Human Subjects Research
Some AI-driven biology research may be subject to federal regulations for human subjects research (HSR). We will provide an overview of what constitutes HSR, give examples of LANL HSR, and explain the review process.                   


## Day 1 (August 26th), Afternoon Session


### Sandrasegaram Gnanakaran   

#### Prediction of virus-host protein-protein interactions


### Bin Hu

#### Learning the language of proteins and predicting the impact of mutations

Mutations in proteins directly impact their structure and function. Understanding the “language” of proteins, or the sequence to function (genotype-phenotype) relationship has many real-world applications. One set of applications includes those in biodefense, such as biological threat detection and biosurveillance, antibody engineering, and medical countermeasure development. In this study, we present a novel language model-based approach that can rapidly analyze vast collections of sequences, and make near real-time functional predictions that compare favorably to those made using conventional bioinformatic and experimental methods. Our findings reveal that tailored protein language models can predict protein mutation phenotypes, such as binding affinity or level of expression, when they are trained with high-throughput functional data. Protein language models applied to viral genomes can also discern the lineage within a family (e.g., sarbecovirus sequences). Coupled with sequenced-based biosurveillance, this type of model may provide early warning signals of potential zoonotic spillovers (i.e. host jumping) or “escape” from existing medical countermeasures posed by novel mutations. This research not only underscores the potential of ML and language models in addressing pressing challenges in understanding the mapping of sequence to function, but further elucidates their potential application in accelerating the response to biological threats as they evolve.

### Blake Hovde                

#### NLP trained on biological literature, for protein and plasmid analysis

AIMBOTS (Automated Iterative Multi-BLAST for Obscure Target Sequences) is an automated annotation tool for screening complex DNA sequences of unknown function.  Applications include deconvoluting wastewater and soil and human metagenomics data.  We are currently investigating the use of biologically trained LLMs for classifying large volumes of DNA sequencing data that have been annotated with gene and protein names, and attempting to distill/summarize the information using LLMs for easy human user digestion of the biological information.

### Jason Gans                

#### A cross-validation framework for data clustering by protein sequence similarity

Accurate computational prediction of protein-protein binding affinities has the potential to significantly decrease the time and cost for designing proteins that can specifically bind to biologically relevant target proteins for detection, diagnostic and therapeutic applications. While recent advances in the field of de novo protein design offer the possibility of using computationally designed proteins as affinity reagents, current protein design methods do not predict the strength of protein-protein binding (e.g., the equilibrium binding constant Kd).

Quantitative computational prediction of protein-protein binding affinity is a challenging problem. Atom-level simulations of protein-protein binding are time consuming and resource intensive (typically requiring large computer clusters) due to the large number of protein and solvent degrees of freedom that must be computationally explored. Machine learning (ML) offers a potentially faster method for predicting protein-protein binding affinity by associating patterns in amino acid sequence and/or 3D protein structure with experimentally measured Kd values. However, ML-based prediction of protein-protein binding affinity is challenging due to (a) the limited amount of independent training data (due to the presence of homologous proteins in publicly available data), and (b) the large number of possible ways to computationally represent a pair of proteins in a ML algorithm (i.e., feature selection). Groups of similar proteins can confound naïve attempts to assess affinity prediction accuracy using cross validation by randomly partitioning closely related protein pairs into both training and testing sets (leading to overly optimistic estimates of prediction performance).

To account for similarity-induced biases in the available datasets of protein-protein binding affinity, the DTRA-funded BioRAD project has developed a cross validation framework that hierarchically clusters the available input data (consisting of 3D protein heterodimer structures and associated Kd values) by protein sequence similarity. At each level of this hierarchy, cross validation is performed on clusters of protein pairs (as opposed to individual protein pairs). This process provides an increasingly stringent evaluation of ML prediction methods and how accurately binding affinity predictions can generalize to protein pairs not previously encountered. Using this cross validation approach, different ML models were evaluated using experimental protein heterodimer 3D structures and associated Kd values collected from the open literature by the PDBBind database. The results demonstrate that the proposed cross validation framework can guide the selection of ML models that more accurately predict the binding affinity for previously unknown protein pairs.

### Michael Wall              

#### Some Novel Applications for Molecular-Dynamics Simulations of Biomolecules





## Day 2 (August 27th), Morning Session


### Manish Bhattarai    

#### DNA Breathing Integration with Deep learning Foundational Model Advances

To ascertain the precise relationship between TF binding and DNA breathing, we developed the multi-modal deep learning model  EPBDxDNABERT-2, which is based on the Extended Peyrard-Bishop-Dauxois (EPBD) nonlinear DNA dynamics model. To train our EPBDxDNABERT-2, we used chromatin immunoprecipitation sequencing (ChIP-Seq) data  comprising 690 ChIP-seq experimental results encompassing 161 distinct TFs and 91 human cell types.  EPBDxDNABERT-2 significantly improves the prediction of over 660 TF-DNA, with an increase in the area under the receiver operating characteristic (AUROC) metric of up to 9.6% when compared to the baseline model that does not leverage DNA biophysical properties. We expanded our analysis to in vitro high-throughput Systematic Evolution of Ligands by Exponential enrichment (HT-SELEX) dataset of 215 TFs from 27 families, comparing EPBD with established frameworks. The integration of the DNA breathing features with DNABERT-2 foundational model, greatly enhanced TF binding predictions. Notably,  {EPBDxDNABERT-2, trained on a large-scale-multi-species genomes, with a cross-attention mechanism, improved predictive power shedding light on the mechanisms underlying disease-related non-coding variants discovered in genome-wide association studies. 

https://www.biorxiv.org/content/10.1101/2024.01.16.575935v2.abstract
https://github.com/lanl/EPBD-BERT 
      

### Juston Moore       

#### Local Latent Space Bayesian Optimization for Drug Discovery

Bayesian optimization over the latent spaces of deep autoencoder models (DAEs) has recently emerged as a promising new approach for optimizing challenging black-box functions over structured, discrete, hard-to-enumerate search spaces (e.g., molecules). Here the DAE dramatically simplifies the search space by mapping inputs into a continuous latent space where familiar Bayesian optimization tools can be more readily applied. Despite this simplification, the latent space
typically remains high-dimensional. Thus, even with a well-suited latent space, these approaches do not necessarily provide a complete solution, but may rather shift the structured optimization problem to a high-dimensional one. In this paper,
we propose LOL-BO, which adapts the notion of trust regions explored in recent work on high-dimensional Bayesian optimization to the structured setting. By reformulating the encoder to function as both an encoder for the DAE globally and as a deep kernel for the surrogate model within a trust region, we better align the notion of local optimization in the latent space with local optimization in the input space. LOL-BO achieves as much as 20 times improvement over state-of-the-art latent space Bayesian optimization methods across six real-world benchmarks, demonstrating that improvement in optimization strategies is as important as developing better DAE models.

### Shounak Banerjee    

#### Learning Growth Curves: Algae Crops vs Harmful Algae Blooms


### Sayera Dhaubhadel   

#### Suicide veteran predictions using transfer learning

Transfer learning is an approach in machine learning aimed at improving the performance on a problem of interest with limited data by transferring the knowledge captured by training on different, but related, source domains. Transfer learning is a fundamental concept in the use of foundational models like GPT-4 and LLAMA-3, trained with huge quantities of related data to learn the core concepts, that involves leveraging broad knowledge in such models by fine-tuning the model to answer a more specific problem of interest with limited labeled data. 

AI for healthcare is exciting with numerous possibilities to improve patient care and precision medicine. Yet, the observational nature of medical data makes it difficult to accurately characterize disease risk and the effect of treatment/mitigations. I will start the presentation introducing transfer learning and how it is applied across different problems. Then I will talk about our recent work on predicting suicide risk amongst 4.2 million active VA patients from their longitudinal medical records spanning over 20 years. I will focus on the major challenges, lessons, and solutions we found in modeling this risk prediction problem. In particular, I will talk about importance of problem formulation and variable definition, handling observational biases and confounding effects, incorporation of prior knowledge, multimodal data, distributional shift and generalizability of the model, and high dimensional prediction with limited examples using transfer learning. Finally, I will discuss how attributes of our healthcare outcomes analysis generalize to other LANL-related AI problems.



## Day 2 (August 27th), Afternoon Session


### Sara del Valle      

#### Harnessing Large-Scale Unstructured Data to Understand Public Perception

Social media has become a crucial platform for the global dissemination of information, significantly shaping public perception of events. Much of this online content is conveyed through narratives, which can be analyzed to understand the structure and evolution of various topics. In this talk, I will present a study that explores the temporal evolution of topics within pro- and anti-vaccination discourse, using natural language processing (NLP) and temporal network analysis tools to characterize shifts in public perception over time. 
   

### Casey Gibson        

#### Improving ML based infectious disease forecasting through mechanistic constraints

Outbreak forecasting is the science of predicting future epidemiological outcomes such as case counts or hospital admissions. While forecasting efforts aided public health responses and decision-making during the COVID-19 pandemic, their periodic inaccuracy highlighted that methodological improvements were needed. Here, we developed a model-augmentation methodology that can flexibly incorporate epidemiological dynamics into a broad-class of empirical forecast models (i.e. models that forecast based on historically observed statistical relationships or data). We highlight our methodology through adding peak awareness to three commonly used empirical forecast models including an (1) Autoregressive integrated moving average (ARIMA), (2) Holt-Winters, and (3) Spline model. We find that the peak-aware versions outperform their base counterparts by 9.1% (range: 8.2-12.5%) for COVID-19 hospital admissions from October 12, 2020 to September 11, 2023 and 19.5% (range: 17.6-23.2%) for influenza hospital admissions from January 10, 2022 to May 15, 2023. During epidemiological peaks we see an average forecast performance improvement of 20.7% and 25.4% for COVID-19 and influenza respectively, highlighting how peak awareness improves the forecasts during these critical and historically difficult to forecast time periods. We additionally tested the methodology on the gold standard ensemble models produced by the COVID-19 and Influenza Forecast hubs and found that it improved their performance by 10% and 5% respectively. Our results lay the framework for flexibly incorporating epidemiological dynamics into a wide-range of empirical models and suggest that model augmentation can reliably improve forecasts during key time periods.



### Yen Ting Lin       

#### Bayesian inference for SARS-CoV-2 pandemic




### Ruian Ke           

#### A graph theory and machine learning approaches for identifying rapidly expanding SARS-CoV-2 lineages using early genetic data

With dozens or hundreds of minor variants of SARS-CoV-2 circulating in the global population, there is an urgent need for predicting the scale and the rate of the spread of a new variant when it emerged in the population. This would allow for more focused experimental efforts and for timely formulation of new vaccines.  To address this need, we employed a graph theory + machine learning approach to extract features of rapid epidemic growth from pairwise distance matrices derived from genetic sequences of SARS-CoV-2 lineages. Using these features, our model is able to scan a large amount of SARS-CoV-2 genomic data and at the same time make predictions to identify the future-dominating lineage when its frequency was still low (e.g. <5%). Overall, this approach represents a promising new phylogenetic-tree-free method for SARS-CoV-2 lineage monitoring and epidemiological inference.

### Qianying Lin        

#### Model-based Deep Learning Inferential Framework for Genomic Reassortment

Genomic reassortment is a complex procedure that allows viruses with genomic segments exchange genetic materials during co-infected in the same cell after a host is dually infected by distinct viruses, with potential to produce highly contagious new variants.
With its intrinsic genetic complexity, common phylogenetic and phylodynamic methods are no longer proper to infer the reassortment pattern and biological mechanism.
In this talk, we first present a simulator that simulates both the viral transmission among host population and the within-host viral evolution simultaneously when putting them in the context of a epidemiological model.
We further build a likelihood-free mapping between the epidemiological model of interest and the genomic data and use it for reassortment inference using typical neural network models.




[back](./)

# FSR
Automated Classification of Requirements-related Provisions in Food-safety Regulations

## Description

In this paper, we propose to develop 1) a conceptual characterization of food-safety concepts that closely relate to systems and software requirements and 2) a BERT-based approach to automatically classify legal provisions according to requirements-related food-safety concepts. We empirically evaluate our classification approach with BERT variants, e.g., BERT large, RoBERTa, ALBERT and non-transformer models including: BiLSTM and Keyword Search.
An overview of the approaches are discussed below:
![Alt text](https://drive.google.com/uc?id=1w-H2pt7RBCNpUqqB5eE3EkPnO59A8EwT)

* Pre-processing
* LM-based Classification
* Keyword-based Classification
* Label Prediction


## Content description
* Code: contains scripts related to the implementation of all the approaches in this paper. It contains two subfolder namely RQ1 and RQ2. As the name suggests, RQ1 contains code related to the BERT-based Language Models implemented for answering RQ1 and RQ2 contains code for BiLSTM and Keyword Search baseline models. 
* Evaluation Results: contains two subfolder namely RQ1 and RQ2. 
    *RQ1 includes Precision, Recall and F-Score for the BERT variants classification results, along with the model hyperparameters and statistical significance tests of comparing BERT base approach against these BERT variants.
    *RQ2 includes BiLSTM hyperparameters and statistical significance tests of comparing our approach against baselines.
* Data: contains datasets 

### Instructions to run the proposed algorithms

* How to run the program
* Step-by-step bullets

code blocks for commands


## Help

command to run if program contains helper info
``


## Authors
Shabnam Hasani
s.hassani@uottawa.ca

## Version History

* 0.1
    * Initial Release

## License


## Acknowledgments

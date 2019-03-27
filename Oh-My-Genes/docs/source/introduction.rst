Introduction
============
    This document is intended to specify exact requirements for project OMG.
    The goal of project OMG is to implement a web application for identifying 
    gene expression differences。


Purpose
-------
    Help biologists or people learning gene expression visualize 
    their research data.


Overview
--------
    The web application has a Succinct interface with a single button 
    named upload. Our user upload a plain text file 
    containing gene expression levels from two samples, representing 
    two experimental conditions. The software generates the required 
    charts by parsing text files. The X and Y coordinates of this icon are two 
    samples in the text file, respectively. If an invalid gene expression is given, 
    the web application returns a page informing the user to provide 
    a correct one. 


User Characteristics
--------------------
    *   **Client User:** Biologists who studying the expression of genes.
    *   **Site Maintainer:** Technicians who have the basic knowledge to maintain a website.


Terminologies & Abbreviations Explaination
------------------------------------------
    To introduce the project and specify the requirements in detail, 
    this section is aimed to explain some terminologies and abbreviations, 
    for the sake of better understanding of the content of the project. 

Terminologies
~~~~~~~~~~~~~
    *   *Control sample* - A cell sample prepared in its normal condition.
    *   *Treatment sample* - A cell sample treated by special chemicals, or in which some genes are altered.
    *   *Differentially expressed genes* - The genes which have significantly different expression levels between two samples.
    *   *Up-regulation* - A gene is said to be up-regulated if it has higher expression in treatment than in control.

Abbreviations
~~~~~~~~~~~~~
    *   *OMG* - Oh My Genes
    *   *logFC* - log fold change of gene expression. log_2 [T/C], where T is the gene
        expression level from a treatment sample, while C is the gene expression level from a
        control sample

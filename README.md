# Field Phenotyping with Natural Language

Please visit: https://dill-picl.org/



# New methods in computational linguistics enable researchers to describe phenotypes using natural language and discover trait associations.

## Abstract

Computational linguistics techniques stand to revolutionize how researchers document and compute on phenotypic descriptions. Here we propose to use speech recognition along with Natural Language Processing (NLP) and Machine Learning (ML) for speech-to-text reporting of spoken phenotypic descriptions. We hypothesize that datasets generated in this way can be used for association genetics (and various other applications) irrespective of whether and how those descriptions adhere to current standards for trait data collection. To conduct this investigation, we will use unique two-dimensional (2D) barcodes that will be created for each maize plant in the field. A mobile cellular device application will be developed to scan each barcode and will be used to collect spoken phenotypic descriptions (including measurements) for each plant. Computational methods to determine semantic similarity among phenotypic descriptions will be applied (see Braun and Lawrence-Dill at https://doi.org/10.1101/689976 for methods detail). Using these methods, we will crowdsource phenotypic descriptions and compare the performance of a group of experts to a group of non-expert citizen scientists to determine whether subject matter expertise is necessary for biologically meaningful semantic similarity networks.

## Background

### Current Field Phenotyping Practices

Whereas geneticists describe phenotypes using representative images and language-based descriptions that are freeform, breeders more often measure a set of specific traits across many plants based on specific counts and measurements that adhere to clearly articulated data formats (e.g., stand count, plant height, stalk lodging; [reviewed in 1]). More recently, sensors have been developed and deployed via mobile phenotyping platforms that allow researchers to measure phenotypes and traits and phenotypes over time (e.g., photosynthetic rates [reviewed in 2]). These standards attempt to make field phenotypic data collection structured and efficient to enable computational analysis as well as to minimize human labor.

### Computational Approach to Phenotypic Analysis

Both geneticists and breeders seek to identify the loci that confer specific phenotypes and traits. Geneticists follow up on identified loci with a general interest in determining mechanisms of action that underlie biological phenomena whereas breeders manipulate and recombine variations and alleles to improve traits of interest. Because the genes that confer specific traits act across metabolic and regulatory networks, their identification and relationships to each other are necessarily complex. To simplify computation, researchers have standardized data collection; they have simplified and reduced the information content in phenotypic descriptions to enable computability. NLP and ML are now capable of computing on complex language, and ontology-based structured representations of phenotypic descriptions as entity-quality (EQ) statements can be generated automatically [reviewed in 3 & 4; see also poster by Braun and Lawrence-Dill]. Here we describe how to extend that work to benefit phenotype collection in the field environment.


### Overview of the Methods of the Process of Spoken Descriptions to Semantic Similarity Analyses

![flowchart1](https://github.com/C-Yanarella/Field_Phenotyping_with_Natural_Language/blob/master/flowchart_1.png)

Figure 1: Process to adapt speech for use in semantic similarity analysis. Tan boxes indicate an overview of the steps in our novel method. The left purple box illustrates the functionality of the application being developed. The right green box demonstrates the portion of the process for which we have a working model [described in 4].

We will collect spoken descriptions of plant phenotypes into a system that produces structured EQ statements from text. These text descriptions will then be used to produce semantic similarity networks, which can be queried to determine whether known phenologs are highly connected. 

### Overview of the Workflow for Data Collection and Analysis

![workflow1](https://github.com/C-Yanarella/Field_Phenotyping_with_Natural_Language/blob/master/workflow_1.png)


Figure 2: Workflow for the spoken in-field phenotyping application and subsequent analyses. The tan boxes indicate a steps in the application workflow.

Unique 2D barcodes will be placed on plants out in the field for use as identifiers. The 2D barcodes will be scanned with the application that is being developed to access the information for the individual plant. The application will record spoken phenotypic observations made by two groups: experts and non-experts (citizen scientists). Once phenotypic descriptions are converted to text and analyzed via NLP and ML, phenotypic similarity networks will be created. Comparison of whether and how each group’s derived phenotypic similarity network can be used to recover known relationships among genes that confer shared traits will reveal whether and how expertise is required for field phenotyping work. 


## Significance

This research will transform the current procedures for phenotyping plants in the field. Recording spoken phenotypic data using cellular devices will make data collection more efficient. Additionally, the phenotypic similarity networks produced from non-expert citizen scientists’ phenotypic descriptions can be compared to those from expert curated descriptions to further our understanding of the role of expertise and to help researchers to decide where best to spend valuable time.

## Citations

1. The Genomes to Fields Initiative. GxE Field Experiment 2019 SOP v.3.August 2019.
2. Barker J, Zhang N, Sharon J, Steeves R, Wang X, Wei Y, and Poland J. Development of a field-based high-throughput mobile phenotyping platform. Comp Electr Agric. 2016:122:74-85. doi: 10.1016/j.compag.2016.01.017.
3. Mabee PM, Ashburner M, Cronk Q, Gkoutos GV, Haendel M, Segerdell E, Mungall C, Westerfield, M. Phenotype ontologies: the bridge between genomics and evolution. Trends in Ecology & Evolution. 2007 Apr 9; 22(7), 345–350. doi: 10.1016/j.tree.2007.03.013.
4. Braun IR, & Lawrence-Dill CJ.  (2019).  Automated methods enable direct computation on phenotypic descriptions for novel candidate gene prediction. bioRxiv. 2019 July 3. doi: 10.1101/689976.

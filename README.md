# Machine-Learning
Supervised and unsupervised learning assignment from the Machine Learning Subject of the Computational Biology Masters Degree (UPM).


## Supervised Learning Assignment:

### Description
Colorectal cancer (CRC) is one of the principal causes of death and its early diagnosis and
treatment can lead to a full recovery. It is also known that different individual response
differently to the treatment due to its genetic information. The data for this activity contains
information ('MM','WW','WM', 'MW') of different SNPs (Single-Nucleotide polymorphism) from
different individuals that have been diagnosed with rectal colon cancer and the categorization
of them based on its good response (R) or bad response to the treatment (NR). The datasets are
included in this activity and numbered from 1 to 33 and you have to select your assigned dataset
to do the activity. You can find the list of the assigned datasets in the StudentsDatasets.pdf file.

The dataset contains 53 individuals (rows), 21 features (associated to different SNPs), and 1 target value (‘Target’). The values of the data files are already transformed to 0 for ‘MM’, 1 for ‘WW’ and 2 for ‘WM’ values in order to be compatible with all the ML learning models format.

### Objectives
Development of a machine learning model which can classify if an individual will response well or bad to the treatment based on its SNPs information using the included dataset.
  
### Methodology
Perform a comparative study using the different machine learning classifiers (Logistic Regression, Decision Trees, KNN, Random Forest, and Multilayer Perceptron) and obtain the best possible model (adjust the parameters of the models using cross-validation or any other validation method).
    
    
## Unsupervised Learning Assignment:
### Description
I have analyzed the NCI-60 Human Tumor Cell Lines Screen provided by the National Cancer Institute (https://dtp.cancer.gov/discovery_development/nci-60). It utilizes 60 different human tumor cell lines to identify and characterize novel compounds with growth inhibition or killing of tumor cell lines. The original dataset has been modified to minimise its noise. Genes with variability above a threshold have been filtered out to generate normalised RNA abundance data. 

NCI60 is a dataset of gene expression profiles of 60 National Cancer Institute (NCI) cell lines.
These 60 human tumour cell lines are derived from patients with leukaemia, melanoma, along
with, lung, colon, central nervous system, ovarian, renal, breast and prostate cancers. This
panel of cell lines have been subjected to several different DNA microarray studies using both
Affymetrix and spotted cDNA array technology.

### Objectives
1. Cluster the data using hierarchical and partitional unsupervised learning models to
analyze how similar these cancers are based on gene expression.
2. Find out if there is any similarity related to tissue of origin.

# BIOINF-593
Repository for course project for Machine Learning in Computational Biology

[Link to Slide](https://docs.google.com/presentation/d/1P6bJaGGyj0-j0dq4IGDtY9T8MlRkfDr9U-2VIEzmhT8/edit?usp=sharing)  

The slides have additional details about the datasets that are used and a graphical workflow of the overall project (TBD)

[Link to Dropbox Data](https://www.dropbox.com/home/BIOINF593)

Dropbox contain raw data downloaded from various sources, and also the modified/combined datasets.


###########____________OVERALL PROJECT RATIONALE________________###############

Metastasis from primary tumours are bad.
difficult to tell if a tumour has metastasized or not
we want to find a method to predict:
  - Based on gene expression of primary tumour
  - can we predict whether there is hidden metastasis event?


###########____________OVERALL PROJECT WORKFLOW/METHODS________________###############

- download dataset from various studies
  - normalize data by TPM or sth
  - normalize data by other methods?
  - make a combined dataframe
- make learning model
  - machine learning stuff, idk.
- do prediction on extra data
  - get primary tissue data from TCGA
  - divide patients by whether these patients have metastasis prediction.
  - do survival analysis on the 2 groups.

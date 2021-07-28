Emily Lorenzen

Metis Bootcamp - Deep Learning

Project Proposal

7/28/2021

# Predicting immune system response to chemokines and cytokines through cellular imaging

## Question/Need:
The process of drug development is both resource and time intensive. Understanding a drugs mechanism of action (MOA) and target can increase the chances of clinical approval. However, elucidating the MOA and target protein is not a trivial process. Many complementary experimental techniques must be used in combination. Image-based profiling provides much more information in a single assay than traditionally used techniques in drug discovery. In order to inform the emerging field of image-based profiling in application to MOA determination, it is necessary build an algorithm that can accurately predict an MOA based on cellular images. In this project, I will use data of cells treated with drugs whose MOA has been previously determined.

## Data:
Data will be downloaded from Imaging Data Repository (IDR), a public database of cellular images produced in high-throughput studies. The dataset of interest is IDR0088, where 15 different cell types were treated with 1,008 differrent drugs with known mechanisms of action. The corresponding publication can be found at https://www.nature.com/articles/s41598-020-69354-8

Each sample was imaged by spinning disk confocal microscopy, in three different areas, and using three channels to capture nucleo, TUBA1B, and RELA. 

## Tools:

Pandas will be use for handling metadata

Omero and IDR will be used to access imaging data.

Keras will be used to build a convolutional neural network. 


## Minimum Viable Project:

For a minimum viable project I will focus on building a neural network model for just one cell line and in one channel. 
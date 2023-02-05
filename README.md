# TUSK final project

The aim of the project is to group the students into the clusters by their answers to the studying questions. The project is done as a part of the UpSkilling Program as UofT and Vector institute ([Machine Learning Software Foundations](https://tusk.utoronto.ca/programs/course-details/machine-learning-software-foundations))

## Data
The data consists of answers (correct or not) given by the student for some question. Of course, not all the questions were answered, that makes the matrix very sparse. Also, the metadata (characteristics) of students and question were given, but was not used in this project. 

## Methodology
In this project I compared the following clustering algorithms: Hierarchical, K-means, Spectral clustering and Gaussian mixtures. The evaluation is based on two factors: interpretability (we need to get interpretable clusters) and accuracy (predict the answers from test dataset). Additionally, I discuss several methods how to fill the NaN values in the data and choose the distance.


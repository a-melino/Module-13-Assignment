# Module-13-Assignment - Venture Funding with Deep Learning

### by Alex Melino

#

## Overview of the Analysis

This assignment covers neural network machine learning, and applies neural networks modelling to predict successful applicants for a venture capital firm called Alphabet Soup. The dataset used (found in the 'Resources' folder of this repo as 'applicants_data.csv') consists of historical funding activity from over 34,000 previously funded organizations.

The assignment (found in this repo as 'venture_funding_with_deep_learning.ipynb') begins with reading and preparing the data and splitting it into training and testing sets. The training sets were then used to create a neural network models which provided a prediction of potential success. The results were analyzed by assessing accuracy with the test sets.

Two additional neural network models were then created by tweaking with the neural network parameters, the number of epochs, and the input data in order to attempt to obtain more accurate results. The increases in accuracy gained from the additional neural network models was negligible. Additional iterations of models are necessary to see a larger increase in accuracy.

All three neural networks (the original and then two alternatives) were saved as .h5 files and can be found in the 'Resources' folder of this repo.

The libraries and dependencies used in this analysis are pandas, pathlib, sklearn, tensorflow and keras.

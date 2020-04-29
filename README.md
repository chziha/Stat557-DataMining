# Fast Prediction of the Nanocrystal Shape through Machine Learning
This repository includes the course work for [Stat 557 - Data Mining](https://bulletins.psu.edu/university-course-descriptions/graduate/stat/)

## Motivation
Predicting of the nanocrystal shape using conventional computational methods like [Molecular Dynamics simulation](https://en.wikipedia.org/wiki/Molecular_dynamics) can be very time consuming, we hope to construct a faster model through different machine learning algorithms to predict the nanocrystal shape, using geometric characteristic of the nanocrystal seed as features.

## Installation
This project requires Python 3.x and the installation of [Anaconda](https://www.anaconda.com/) or another software to execute the [Jupyter Notebook](https://jupyter.org/). Packages required include: pandas, numpy, matplotlib, seaborn, sklearn, pylab, itertools, and graphviz.

## File Descriptions
data_original.csv in the folder is the data for use.<br/>
predict_shape.ipynb is the main file containing the code and analysis.

## Summary
* PCA gives an overall accuracy around 94%, but it fails in classifying shape 2.
* SVM enhanced the accuracy to 97% and have good performances in predicting all shapes.
* Random forest further increases the predictive accuracy to 98%.

## Acknowledgements
Author: Zihao Chen and Tianyu Yan

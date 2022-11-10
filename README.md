# CM4044 proj 2

A mini project for CM4044-AI in Chemistry. This is a graded assignment for a CBC year 4 chemistry module in NTU. 

First attempt on using RDkit, sklearn, deepchem to come out with different inputs to feed a regression model. In this project, we extracted 2 types of fingerprints using RDKit. Next, we used Mol2vec (1) and Graph2vec (2) to generate vector embeddings and fitt them into 4 different regression models from sklearn and evaluated them. 

The codes were written in conjunction with my 2 other friends, Ding Jie and Zhi Chao.

This repository consist of:
  1) cm4044_proj2.ipynb. A Jupyter notebook consisting of all our codes from loading dataset to generating embeddings and then evaluating the results 
  2) csv folder. CSV folder containing the original data, 4 different embeddings using different methods. 
  3) results folder. A result folder containing all the predicted values from using all 4 different methods. 

Ref:
1) Mol2vec: Unsupervised Machine Learning Approach with Chemical Intuition
Sabrina Jaeger, Simone Fulle, and Samo Turk
Journal of Chemical Information and Modeling 2018 58 (1), 27-35
DOI: 10.1021/acs.jcim.7b00616

2) Narayanan, A., Chandramohan, M., Venkatesan, R., Chen, L., Liu, Y., Jaiswal, S. graph2vec: Learning Distributed Representations of Graphs. 2017

3) John S. Delaney
Journal of Chemical Information and Computer Sciences 2004 44 (3), 1000-1005
DOI: 10.1021/ci034243x


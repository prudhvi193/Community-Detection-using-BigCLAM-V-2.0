# Community Detection using BigCLAM V-2.0

This project was developed as part of my Master's Course Study in Algorithms and Methods of Big Data Analytics.

Authors: Prudhviraj Sheela

The main motive of this project is to understand the fine details of implementing community detection using BigCLAM Version 2.0 Algorithm. In specific, I have developed an algorithm to find overlapping communities in the given network which states that a node can be represented in multiple communities in the given network. The algorithm formulates the community detection as a non-negative matrix factorization with maximum log-likelihood estimation problem by parameterizing node strength in communities. The process flow includes 4 phases of execution and they are:

a)Factor Matrix Initalization for the given seed communities and for random sample data.

b)Matrix Factorization using Big Clam V2.0 for all the three types of factor matrix initializations.

c)Community Assignments for deciding the membership of each node in each community.

d)Evaluating the obtained community assignments data with the ground truth communities data using the factor of recall and plotting a graph between the associated recall scores and the types of factor matrix initializations.

IDE Used: Google Colab Notebook

Language Used: Python

Description about the files:

1)Project-5.pdf: The file contains the steps associated for developing the application and also the intermediate output formats for executing the program.

2)Community_Detection.py/Community_Detection.ipynb: Python community detection program developed using BigCLAM Version 2.0 for all the three different type of factor matrix initalizations and the associated internal computations.

3)groundtruth_communities.txt: This data is a space seperated file, where each node-id with a set of node id's represent a ground truth community

4)YouTube.edgelist: Curated Data sample of the YouTube social network and this data file consists of 7675 nodes, 35,622 edges, and 29 ground-truth communities. This file should be loaded using the networkx package.

5)20percent_seed_communities.txt: This is space separated file, where each line, with a set of node ids, represent a community and can be used to initialize all communities.

6)neighborhood_seeds.txt: This is space separated file, where each line, with a set of node ids, represent a community and can be used to initialize all communities.

Output Files: The explanation about the output generated is available in "Community_Detection.ipynb" python file which explains clearly each step on how is the end result obtained.

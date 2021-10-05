# ICS2205 - Web Intelligence

### Task 1: Graph Analytics
The aim of this task is to use the given Twitter dataset and to perform some analyses on the underlying mention graph.
The mention graph is a directed graph where the vertices are the users and the edges represent the mentions. 
Thus userA - [mentions -> userB. The number of times that userA mentions userB can be transformed into a weight.
A number of different graph analytics were then performed including:
* Number of nodes and edges
* Indegree and outdegree
* Degree distribution
* Average path length
* Global clustering coefficient
* Closeness
* Betweenness centrality
* Visualisations (the larger the weight, the larger the nodes)

### Task 2: Information Retrieval
The aim of this task is to build a simple Information Retrieval engine that uses the Vector Space model to find documents related to a user query.
After reading, tokenising case-folding, stemming and removal of stop words, the TF.IDF weight for each term is calculated.
Cosine similarity is then used to calculate the similarity between the query, inputted by the user, and each document returned in the previous step.
Finally a ranked list of the most mathcing documents is outputted.


# Information-Retrieval

This project is an implementation of an information retrieval system which uses a large dataset of a news agency documents. 

# [Phase 1](/IR_Phase1.ipynb)
This part of the project inlcudes the following:
* **Document preprocessing**
  * Normalization using Parsivar library
  * Extracting tokens
  * Removing stopwords
  * Stemming
  * Checking Heaps' law and Zipf's law before and after stemming
 
* **Positional index construction**
* **Query processing**
  * Normal queries
  * phrase queries
  * boolean queries (NOT)

# [Phase 2](/IR_Phase2.ipynb)
In this part of the project, queries and documents are represented as vectors. Documents are ranked according to their proximity to the query in the vector space. This includes the following steps:
* **tf–idf weighting**
* **Ranking documents based on cosine similarity**
* **Speeding cosine computation by pruning**
  * Index elimination
  * Champion list

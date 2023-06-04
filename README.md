# Duplication-Detection-System

_**Techniques**_: Minhash/LSH, Jaccard Similarity <br />
_**Tools**_: Spark, SQL <br>

## Datasets
**articles1.csv.zip**
The reference article  <br /> 
69716, “California lifted its mandatory water restrictions - that could be a huge mistake”. <br /> 
The reference article should be excluded from the output.

## Objective
Detecting copying and plagiarism using the Minhash/LSH algorithm which relies on the concept of distances to define similarity. <br /> 
For this exercise, use Jaccard similarity.

## Method
Minhash/LSH is an algorithm based on cryptographic hashes that computes similarity between a pair of entities. It is heavily used in Web Search and product similarity. Details of the algorithm can be found in Chapter 3 of Mining Massive Datasets. http://infolab.stanford.edu/~ullman/mmds/ch3.pdf


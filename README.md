# Duplication-Detection-System

_**Techniques**_: Minhash/LSH, Jaccard Similarity <br />
_**Tools**_: Spark, SQL <br>

## Datasets
* **articles1.csv** include data on articles 
* The attributes are **id, title, publication, author, date, year, month, url, and content** <br />
<img width="600" alt="Screen Shot 2023-07-16 at 9 57 19 PM" src="https://github.com/SeungPang11/Duplication-Detection-System/assets/67944800/15ff9e52-e091-4e25-8b7d-565d9b9daa3d"> <br />

* The following reference article will be used to find duplicate articles <br /> 
* **69716**, “California lifted its mandatory water restrictions - that could be a huge mistake”. <br /> 
The reference article should be excluded from the output.

## Objective
* The project aims to build a scalable and effective system to detect copying and plagiarism <br />
  using the **Minhash/LSH** algorithm, which relies on the concept of distances to define similarity. <br /> 
  For this exercise, **Jaccard similarity** is used to calculate the distance. <br /> <br />
* **Minhash/LSH** is an algorithm based on cryptographic hashes that compute the similarity <br />
  between a pair of entities. It is heavily used in Web Search and product similarity.  <br />
  Details of the algorithm can be found here: http://infolab.stanford.edu/~ullman/mmds/ch3.pdf <br />

## Method
<img width="731" alt="Screen Shot 2023-07-16 at 9 57 39 PM" src="https://github.com/SeungPang11/Duplication-Detection-System/assets/67944800/c7c70cb0-e5cd-4c0b-8880-05f6989a9929">

<img width="907" alt="Screen Shot 2023-07-17 at 7 35 07 PM" src="https://github.com/SeungPang11/Duplication-Detection-System/assets/67944800/128c32c6-028f-44dd-b8a0-a347bbb49306">




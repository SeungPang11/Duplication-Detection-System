# Duplication-Detection-System

_**Techniques**_: Text-Preprocessing, Minhash/LSH, Jaccard Similarity <br />
_**Tools**_: Spark, SQL <br>

## Datasets
* **articles1.csv** includes data on over 50,000 articles 
* The attributes: **id, title, publication, author, date, year, month, url, and content** <br />
<img width="500" alt="Screen Shot 2023-07-16 at 9 57 39 PM" src="https://github.com/SeungPang11/Duplication-Detection-System/assets/67944800/c7c70cb0-e5cd-4c0b-8880-05f6989a9929"> <br />

* The following reference article will be used to find duplicate articles <br /> 
* **69716**, “California lifted its mandatory water restrictions - that could be a huge mistake”. <br /> 
The reference article should be excluded from the output. 

## Objective
* The project aims to build a scalable and effective Duplicate Detection System that detects plagiarism <br />
  by using the **Minhash/LSH** algorithm, which relies on the concept of distances to define similarity. <br /> 
  For this project, **Jaccard similarity** calculates the distance. <br /> <br />
* **Minhash/LSH** is an algorithm based on cryptographic hashes that compute the similarity <br />
  between a pair of entities. It is heavily used in Web Search and product similarity.  <br />
  Details of the algorithm can be found here: http://infolab.stanford.edu/~ullman/mmds/ch3.pdf <br />

## Method
* Text Pre-Processing <br />
<img width="500" alt="Screen Shot 2023-07-16 at 9 57 19 PM" src="https://github.com/SeungPang11/Duplication-Detection-System/assets/67944800/15ff9e52-e091-4e25-8b7d-565d9b9daa3d"> <br />

*  <br />
*  <br />
## Output
*  10 most simialr articles sorted by Jaccard Similarity score <br /> <img width="500" alt="Screen Shot 2023-07-17 at 7 35 07 PM" src="https://github.com/SeungPang11/Duplication-Detection-System/assets/67944800/128c32c6-028f-44dd-b8a0-a347bbb49306">




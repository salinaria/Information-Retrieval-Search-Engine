# Information Retrieval course project Fall-1401

#### Developing a simple Persian search engine

# Phase 1

### Pre-processing data
* Tokenizing docs
* Deleting stop words
* Stemming

### Make positional inverted index
* A dictionary containing all words of our dataset
* Store frequency of each word in our dataset
* Sotre every document that a word showed up in it and its frequency and its position in this document

### Retrieve query results
1. Select related document from inverted index
2. Apply query operations (Not and Phrase operations)
3. Score documents respected to:
    1. How many words in query exist in theis document
    2. How many times each word of query repeted in this document
4. Show top-5 results with related sentences of those documents

# Phase 2

### tf.idf

* Calculating tf.idf score and cosine similarity between a query and a document

### Champions list

* Index elimination using champions list to make faster our engine

# Instructor

Information Retrieval course Fall-1401 at Computer Engineering of Amirkabir University of Technology taught by [**Prof. Ahmad Nickabadi**](https://scholar.google.com/citations?user=pSMNSZwAAAAJ&hl=en)

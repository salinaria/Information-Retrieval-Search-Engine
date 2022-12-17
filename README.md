# Information retrieval course project Fall-1401

#### Developing a simple Persian search engine

## Phase 1

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


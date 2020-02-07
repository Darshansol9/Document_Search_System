# Document_Search_System
This is a NLP tasks to search which document out of given web-based documents matches with the query documents

The goal of this problem is to implement a simple and effective Document retrieval system.<br>
Given a database of documents as well as a query document (all provided in an attached data folder) Tasks is to find the document in the database that is the best match to the query.<br>

Approach Implemented:

a. Wrote a small parser to read each document and convert it into a vector of words.<br>
b. Computed tf-idf values for each word in every document as well as the query.<br>
c. Compued the cosine similarity between tf-idf vectors of each document and the query. <br>
d. Reported the document with the maximum similarity value. <br>

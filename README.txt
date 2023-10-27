Exercise: This is some background information 

Customer Complaint Categorization

Context:

Banks often receive various types of customer complaints through emails, chat support, or other channels. Manually categorizing these complaints can be time-consuming and prone to errors. In this exercise, the focus is on automating the categorization of customer complaints by generating document embeddings for each complaint and then classifying them.

Keyword Assignment:
One approach is to look for Keywords in the complaint text and assign a category based on the keywords found. For example, if the complaint text contains the word “credit card”, then the category can be assigned as “Credit Card”. 

Document Embedding:
Here we will embed the documents and then use the embeddings to classify the complaints. We will use the Universal Sentence Encoder to generate embeddings for each complaint. The Universal Sentence Encoder encodes text into high dimensional vectors that can be used for text classification, semantic similarity, clustering and other natural language tasks.



##Chromadb

In this notebook, we will implement the full workflow of text vectorization, vector search, and question answering workflow using Chromadb - an open-source vector database. 

Chroma collection is akin to an index that stores one set of your documents.

Collections are where you will store your embeddings, documents, and additional metadata.

The nice thing about ChromaDB is that if you don't supply a model to vectorize text into embeddings, it will automatically load a default embedding function, i.e., SentenceTransformerEmbeddingFunction. It can handle tokenization, embedding, and indexing automatically for you. 

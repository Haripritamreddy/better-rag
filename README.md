# better-rag

## Overview
**better-rag** is a project that compares two Retrieval-Augmented Generation (RAG) methods:

**Method-1**
1. Using a graph structure to store the data .We use Diffbot to extract entities and relationships from plain text.  We use a neo4j instance to store and query the nodes.
**Method-2**
2. Converting text into embeddings, storing them in Chroma DB, and querying it by similarity search. In this methos we embed both the plain text and user query and we get relevant content if ser query embeddings match the plain text embeddings. 

The results show that the new graph structure method is better than the embedding-based approach.

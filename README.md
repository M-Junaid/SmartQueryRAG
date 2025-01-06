# SmartQueryRAG

**Overview**

This project demonstrates a Retrieval-Augmented Generation (RAG) pipeline using LangChain, Pinecone, and Google's Generative AI models. It involves the following key steps:

1. Setting up a Pinecone vector database.

2. Embedding textual data using Google's Generative AI Embeddings.

3. Storing and retrieving documents based on similarity search.

4. Answering user queries by leveraging relevant retrieved documents and a Large Language Model (LLM).

**Features**

* Document Storage and Retrieval: Efficiently stores and retrieves documents based on cosine similarity.

* Generative AI Integration: Utilizes Google's Generative AI models for embedding and answering queries.

* Customizable Indexing: Supports dynamic document addition and index creation.

* Query Answering: Retrieves contextually relevant information and generates responses using an LLM.

**Prerequisites**
* Python 3.7 or higher

* Google API Key with access to Generative AI services

* Pinecone API Key
  
**Acknowledgments**

* Pinecone: For vector database services.

* Google Generative AI: For embedding and LLM capabilities.

* LangChain: For providing abstractions to work with LLMs and vector databases.

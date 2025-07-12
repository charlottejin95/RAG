# Retrieval-Augmented Generation (RAG) on Large Langurage Model (LLM)

This repository demonstrates how to build a **Retrieval-Augmented Generation (RAG)** system, combining information retrieved from PDFs with generative large language model. This is ideal for building QA systems, knowledge assistants, and context-aware chatbots.


##  Overview

The pipeline includes the following components:

1. **Document Loading**: Load raw documents from a local directory.
2. **Text Splitting**: Break documents into smaller chunks for processing.
3. **Embedding Generation**: Convert text chunks into dense vector embeddings using OpenAI GPT-3.5 model API.
4. **Vector Indexing**: Store and search embeddings using llama_index.
5. **Retriever Setup**: Configure a retriever for semantic similarity search.

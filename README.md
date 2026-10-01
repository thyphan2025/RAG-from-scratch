# Build A Simple RAG From Scratch

This notebook demonstrates how to build a simple Retrieval-Augmented Generation (RAG) system from scratch using Ollama. It covers the following steps:

**1. Loading the dataset:** Cat facts are loaded from a text file.

**2. Implementing the vector database:** Each fact is converted into an embedding vector using Ollama's hf.co/CompendiumLabs/bge-base-en-v1.5-gguf model and stored in a VECTOR_DB.

**3. Implementing the retrieval function:** A retrieve function is created to find the most similar cat facts to a given query using cosine similarity.

**4. Generation phase:** The retrieved facts are used as context in a prompt for a language model (hf.co/bartowski/Llama-3.2-1B-Instruct-GGUF) to generate a response to the user's query.

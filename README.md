# Basic Retrieval-Augmented Generation (RAG)

## Overview
This repository implements a basic Retrieval-Augmented Generation (RAG) system to understand its functionality. RAG enhances language models by retrieving relevant information before generating responses.

## Features
- Uses `BAAI/bge-small-en-v1.5` for embeddings
- Utilizes `TheBloke/Mistral-7B-Instruct-v0.2-GPTQ` for generation
- Implements VectorIndexRetriever for efficient document retrieval

## How It Works
1. **Embedding**: Converts documents into vectors using `BAAI/bge-small-en-v1.5`.
2. **Retrieval**: VectorIndexRetriever fetches relevant documents.
3. **Generation**: `TheBloke/Mistral-7B-Instruct-v0.2-GPTQ` generates responses based on retrieved content.

## Future Improvements
- Hybrid search (BM25 + vectors)
- Fine-tuning for domain-specific knowledge
- Web/API interface
  
Happy coding! 🚀


# Adv_RAG

## Introduction
Adv_RAG (Advanced Retrieval-Augmented Generation) is a pipeline designed for document retrieval and generation tasks using the Retrieval-Augmented Generation (RAG) framework. This pipeline leverages various tools and libraries to efficiently retrieve relevant information from documents and generate responses to user queries.

## Installation
To install Adv_RAG and its dependencies, run the following commands:

```bash
!pip install --upgrade --quiet langchain langchain-openai faiss-cpu tiktoken
!pip install langchain
!pip install openai
!pip install PyPDF2
!pip install faiss-cpu
!pip install tiktoken
!pip install -q pypdf
!pip install torch
!pip install -q transformers
!pip -q install sentence-transformers
!pip install -q llama-index
!CMAKE_ARGS="-DLLAMA_CUBLAS=on" FORCE_CMAKE=1 pip install  llama-cpp-python --no-cache-dir

# Offline LLAMA2 and Milvus for Efficient RAG Creation

This repository contains code for building a Retrieval-Augmented Generation (RAG) system for processing PDF documents using Offline Llama2 as the underlying model and Milvus as the vector store.

*Features:*
PDF Processing: Extracts text data from PDF documents and preprocesses it for further analysis.
RAG Implementation: Utilizes the Offline Llama2 model to perform retrieval and generation tasks.
Vector Store: Stores document embeddings in Milvus for efficient querying and retrieval.

*Install required dependencies:*
pip install langchain pypdf pymilvus
Setup Milvus using the provided script:

*wget https://raw.githubusercontent.com/milvus-io/milvus/master/scripts/standalone_embed.sh*
*bash standalone_embed.sh start*

*Usage:*
Prepare PDF documents: Place PDF files in the designated directory.
Run the PDF processing script to split documents and extract text data.
Initialize Milvus and index document embeddings.
Deploy the Offline Llama2 model using Ollama2.
Build and execute RAG chains for querying PDF documents.

*Dependencies:*
LangChain
PyPDF
PyMilvus

For detailed instructions and usage examples, please refer to the documentation.

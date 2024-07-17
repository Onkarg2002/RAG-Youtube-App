# RAG Application with Pinecone and OpenAI

# Overview
This project demonstrates how to build a simple Retrieval-Augmented Generation (RAG) application that allows users to ask questions about any YouTube video. It uses Pinecone for vector storage and retrieval, OpenAI's API for generating responses, and YouTube's API for fetching video data.

# Features
Fetch and process YouTube video transcripts.
Index video transcripts using Pinecone.
Retrieve relevant video segments based on user queries.
Generate coherent responses using OpenAI's API.
Simple web interface for user interaction.

# Requirements
Python 3.x
Pinecone account and API key
OpenAI account and API key


1. Create a virtual environment and install the required packages:

```bash
$ python -m venv env
$ .env/bin/activate
$ pip install -r requirements.txt
```

2. Create a `.env` file with the following variables:

OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
PINECONE_API_KEY = [ENTER YOUR PINECONE API KEY HERE]
PINECONE_API_ENV = [ENTER YOUR PINECONE API ENVIRONMENT HERE]

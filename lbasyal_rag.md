# Project: RAG-based ChatBot with PDF Integration

## Overview

This project implements a Retrieval-Augmented Generation (RAG)-based ChatBot integrated with PDF documents. The chatbot utilizes models like "meta-llama/Llama-2-7b-chat-hf" and "sentence-transformers/multi-qa-MiniLM-L6-cos-v1" for embedding and inference tasks. This repository contains files and resources used in the experimentation and evaluation of the chatbot system.

## Guidelines to Access the Files

You can access the following files to understand the experiment and explore the resources used:

### [lbasyal_RAG_based_chatbot_llama_2_pdf.ipynb](lbasyal_RAG_based_chatbot_llama_2_pdf.ipynb)

This Jupyter Notebook file serves as the main document for the experimentation phase. It details the implementation of the RAG-based ChatBot using PDF integration. The notebook covers the execution of code, testing of model inference, and calculation of ROUGE scores to compare model responses with reference responses.

### [policy-booklet-0923.pdf](policy-booklet-0923.pdf)

This PDF file contains the care insurance policy booklet used as a knowledge base for the chatbot experiment. It provides the foundational information that the chatbot relies on to answer user queries.

### [query_response_pairs.csv](query_response_pairs.csv)

This CSV file contains 35 query-response pairs generated from the policy booklet. These pairs are used for evaluating the chatbot's performance by comparing its responses with human-generated reference responses. Each pair underwent evaluation for accuracy, reasoning, relevance, and completeness.

The queries in this dataset cover a variety of topics from different sections of the policy booklet, ensuring a comprehensive evaluation of the chatbot's capabilities.

## Usage

To replicate the experiment or explore the files:

1. Open [lbasyal_RAG_based_chatbot_llama_2_pdf.ipynb](lbasyal_RAG_based_chatbot_llama_2_pdf.ipynb) in a Jupyter Notebook environment to view the implementation details.
   
2. Download [policy-booklet-0923.pdf](policy-booklet-0923.pdf) to review the care insurance policy used as the knowledge base.
   
3. Download [query_response_pairs.csv](query_response_pairs.csv) to analyze the dataset of query-response pairs used for evaluation.



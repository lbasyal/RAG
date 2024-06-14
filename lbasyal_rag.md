# Guidelines to access the files:

You can open the file, "lbasyal_RAG_based_chatbot_llama_2_pdf.ipynb," to see how the experiment was carried out. For further information, refer to the related files mentioned below.

## lbasyal_RAG_based_chatbot_llama_2_pdf.ipynb:

This is the main file for experimentation purposes to implement the RAG-based ChatBot with PDF. The models used for this purpose are "meta-llama/Llama-2-7b-chat-hf" and "sentence-transformers/multi-qa-MiniLM-L6-cos-v1" as the embedding model. This file provides complete information about the code execution and testing of the model inference. Furthermore, it demonstrates how the ROUGE score is calculated to compare the model response with the reference response.

## policy-booklet-0923.pdf:

This is the data source about the care insurance policy booklet used as a knowledge base for this experiment.

## query_response_pairs.csv:

This file represents 35 query-response pairs generated from the above policy booklet. These query-response pairs are used for experimentation and evaluation between the reference response and the model-generated response for the given query. The pairs were generated with the help of the GPT-4o model from OpenAI and were evaluated and edited from a human perspective in terms of accuracy, reasoning, relevance, and completeness. To prepare these pairs, we adhered to basic standards as per the requirements. In my case, I generated these pairs as clearly and concisely as possible. The pairs include various types of questions taken from diverse pages within the data source. Some questions ask for general information, while others inquire specifically about numbers. I believe the generated query_response_pairs.csv file provides a broader perspective in terms of query generation from random pages in the PDF file.

# GENAI-Financial-Chatbot

To introduce the concept of chatbots in the finance domain and demonstrate how to build a financial chatbot using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG). 
The following steps are outlined:

- Data Preprocessing: Load and format a dataset of financial questions and answers.
- Document Embeddings: Create document embeddings using Hugging Face embeddings and store them in a Vector DB.
- LLM Loading: Load and quantize an LLM (e.g., ZyER 7B LS LLM) for inference.
- Hugging Face Pipeline: Build a Hugging Face pipeline to generate responses from the LLM.
- RAG QA Chain: Construct a RAG QA chain that combines the retriever function from the Vector DB and the LLM.

The resulting chatbot can answer user queries about financial products, services, and policies. 

- Chatbots use natural language understanding (NLP) to interact with users.
- RAG architecture combines retrieval and generative capabilities for improved performance.
- LLMs provide advanced language processing capabilities for chatbot responses.
- Chatbots enhance user experience by providing personalized support and information.
- Financial chatbots are becoming increasingly common in the banking and finance industries.

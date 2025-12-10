RAG-QA-System-with-Memory: Conversational Q&A on Private Documents
This repository hosts a robust Question-Answering (QA) system built on the Retrieval-Augmented Generation (RAG) architecture. It demonstrates how to effectively combine the factual retrieval power of a vector database with the reasoning capabilities of a Large Language Model (LLM) to answer complex queries over private or domain-specific documents.

A core feature of this project is the integration of memory (chat history), allowing the system to handle follow-up questions and maintain context throughout a multi-turn conversation.

🔑 Key Features
Retrieval-Augmented Generation (RAG): Uses a two-step process to retrieve relevant context from documents before generating an answer.

Conversational Memory: Implements a ConversationBufferMemory to store chat history, enabling context-aware follow-up questions (e.g., "Multiply that number by 10").

Vector Database (Chroma): Utilizes ChromaDB for efficient storage and retrieval of document embeddings.

Document Processing: Includes functions to load and chunk data from various formats, including PDF, DOCX, and TXT files.

Custom Prompting: Demonstrates how to use ChatPromptTemplate to enforce specific LLM behaviors, such as translating the response or adhering to strict context-only answers.


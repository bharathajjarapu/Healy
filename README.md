# Healy 🏥💬
A Health RAG LLM Assistant
 
## Overview

Welcome to the **AI Health Chat Assistant** project! This tool leverages state-of-the-art AI techniques to provide users with information on diseases and their treatments. By processing medical PDFs, it can offer insights into symptoms, causes, and recommended medications. Whether you're seeking basic health advice or need information on available treatments, this assistant is here to help!

## Introduction

The AI Health Chat Assistant combines **Retrieval-Augmented Generation (RAG)** and **Large Language Models (LLMs)** to create a powerful and responsive health advisor. It uses two key PDFs:
1. A comprehensive document detailing various diseases and their causes.
2. A guide on medicines and treatments available for those diseases.

By integrating these resources, the assistant can provide accurate and relevant health information in response to user queries.

## Features

- **PDF Processing:** Extracts and processes text from medical PDFs to build a knowledge base.
- **Conversational AI:** Utilizes a generative AI model to interact with users and answer health-related questions.
- **Vector Storage:** Implements FAISS for efficient similarity search, ensuring quick access to relevant information.
- **Streamlit Interface:** Provides a user-friendly chat interface for seamless interactions.
- **Contextual Responses:** Offers health advice based on current medical knowledge and best practices, tailored to the Indian context.

## How It Works

1. **Data Ingestion:** The assistant starts by loading and extracting text from two PDF files. These files contain information about diseases and treatments.
2. **Text Chunking:** The extracted text is split into manageable chunks using `RecursiveCharacterTextSplitter` to facilitate efficient processing and retrieval.
3. **Vector Store Creation:** The text chunks are converted into vector embeddings using Google Generative AI, then stored in a FAISS vector database.
4. **Conversational Chain:** The AI model is set up with a prompt template that guides the conversation based on the user's queries and the context provided.
5. **User Interaction:** Users can ask health-related questions through the Streamlit interface. The assistant uses the vector store to find relevant information and generate responses.
6. **Response Generation:** The AI model generates responses based on the context and previous interactions, providing relevant health advice and recommendations.

## Future Enhancements

- **Fine-Tuned Model:** Integrate a fine-tuned version of LLaMA 3.1 for even more accurate and context-aware responses.
- **Expanded Knowledge Base:** Incorporate additional medical documents and resources to cover a broader range of health topics.
- **Multi-language Support:** Add support for multiple languages to cater to a diverse user base.
- **Enhanced User Experience:** Improve the chat interface with more interactive features and personalized user experiences.

## Conclusion

The AI Health Chat Assistant is designed to be a helpful and accessible for understanding RAG and obtaining health-related information. By leveraging advanced LLMs and medical knowledge, it aims to provide users with reliable advice and recommendations. We hope this project enhances your understanding of health conditions and treatments, making it easier to access the information you need.

Feel free to contribute, suggest improvements, or simply try out the assistant to see how it can help you with your health inquiries!

---

*Happy chatting and stay healthy!* 🩺💡

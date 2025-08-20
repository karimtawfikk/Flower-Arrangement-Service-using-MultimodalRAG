# Flower-Arrangement-Service-using-MultimodalRAG
This project implements a multimodal RAG system that helps users design creative flower arrangements. The system stores and indexes flower images using ChromaDB with OpenCLIP embeddings, allowing natural language queries like “What flowers would look elegant for a wedding bouquet?”.

When a user submits a query:

1-The system retrieves the most relevant flower images from the database.
2-These images are converted into base64-encoded representations and passed, along with the user’s query, to a vision-language model (LLM).
3-The model then generates a personalized, conversational bouquet suggestion grounded in the retrieved images.

This combines image retrieval, multimodal embeddings, and generative AI to provide a unique, interactive tool for floral design inspiration.

Demo:
![WhatsApp Image 2025-08-20 at 13 27 10_908cdb19](https://github.com/user-attachments/assets/12ab475b-37e4-4b8b-a59b-b21447a76f50)
![WhatsApp Image 2025-08-20 at 13 27 35_821dbbf2](https://github.com/user-attachments/assets/4d3d69e0-db30-4f06-9078-8a350b878d15)

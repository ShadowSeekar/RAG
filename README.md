# RAG
RAG (Retrieval-Augmented Generation) system to efficiently retrieve and generate responses to business-related queries about AMD using GenAI

Embeddings: Utilized the DistilBERT model for encoding textual data into semantic embeddings.
• Retrieval: Leveraged Pinecone for semantic search and document retrieval. Implemented chunking and embedding
upload to Pinecone for scalable and fast document retrieval.
• Natural Language Query Handling: Enabled contextual and accurate query responses using OpenRouter’s google gemini
for conversational API integrated with the retrieved information.

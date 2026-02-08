```text
User Input (Text)
      ↓
Text Preprocessing
      ↓
Embedding Generation (ML Model)
      ↓
Vector Database (Semantic Search)
      ↓
LLM with RAG (Insight Generation)
      ↓
Explainability Layer
      ↓
Backend API (FastAPI)
      ↓
Frontend Dashboard / API Consumer

### User Input (Text)
Raw unstructured text such as feedback, reviews, or reports submitted by the user.

### Text Preprocessing
Cleans and normalizes input text by removing noise and standardizing format to improve downstream model performance.

### Embedding Generation (ML Model)
Converts text into dense numerical vectors that capture semantic meaning using an embedding model.

### Vector Database (Semantic Search)
Stores embeddings and retrieves the most relevant context chunks based on similarity search.

### LLM with RAG (Insight Generation)
Uses retrieved context along with the user query to generate accurate and context-aware insights.

### Explainability Layer
Provides reasoning, retrieved sources, or summarized justification for the generated insights.

### Backend API (FastAPI)
Exposes the GenAI pipeline as REST APIs for frontend or external consumers.

### Frontend Dashboard / API Consumer
Displays insights or consumes APIs for visualization or integration.

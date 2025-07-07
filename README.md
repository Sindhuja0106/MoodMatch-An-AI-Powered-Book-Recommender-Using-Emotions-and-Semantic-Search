# MoodMatch-An-AI-Powered-Book-Recommender-Using-Emotions-and-Semantic-Search
MoodMatch is an intelligent book recommendation system that leverages natural language understanding to suggest books based on user-described moods, themes, or emotions.By combining semantic similarity (via embeddings) with emotional tone filtering, it tailors personalized suggestions that go beyond genre — helping users find books that feel right.
🔍 Key Features:

Semantic Search: Understands user queries like “a hopeful story of redemption” using language embeddings.

Emotion Filtering: Re-ranks results based on mood indicators (joy, sadness, fear, anger, surprise).

Category Filtering: Users can refine recommendations by genre (Fiction, Biography, etc.).

Interactive UI: Clean and responsive Gradio interface for real-time, user-friendly interaction.

🧠 Tech Stack:

LangChain for document loading, chunking, and similarity retrieval

OpenAI or Hugging Face Transformers for embeddings (e.g., MiniLM, BART)

Chroma VectorDB for storing and querying embeddings

Gradio for front-end deployment

Pandas & NumPy for data handling and processing

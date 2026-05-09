# Advanced-Multi-Modal-AI-Assistant
"An end-to-end multi-functional AI ecosystem built using Gemini-2.5-Flash . This platform integrates RAG (Retrieval Augmented Generation) for dynamic knowledge expansion , a specialized Medical Q&amp;A system , and a real-time arXiv Research Assistant . It features advanced Multi-modal vision capabilities and Sentiment-aware responses."
Dynamic Knowledge Base (RAG): Uses FAISS vector database and HuggingFace embeddings to retrieve info from custom CSV/Text files . 
Medical Diagnostic Assistant: Specialized chatbot trained with the MedQuAD dataset for healthcare queries.  
arXiv Research Expert       : Fetches and summarizes scientific papers directly from the arXiv API .  
Multi-Modal Vision          : Capable of understanding and describing images uploaded by the user .  
Sentiment & Emotion Analysis: Uses TextBlob to detect user tone and generate empathetic replies via Gemini . 
Multilingual Support        : Auto-detects and translates chat in Tamil, Hindi, French, German, etc .  

AI_Chatbot_Project/
├── app.py (Main Streamlit UI)
├── requirements.txt (Dependencies)
├── dataset.csv (Base Knowledge)
├── faiss_index/ (Vector Store)
├── knowledge_sources/ (Extra Updates)
└── README.md (Project Guide)

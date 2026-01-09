# Building-RAG-from-Scratch

🚀 Built a Retrieval-Augmented Generation (RAG) System from Scratch!
I recently completed a hands-on project where I built a RAG system entirely from the ground up — using tools that real engineers use to build scalable, production-level AI systems.
Here’s a quick breakdown of the tools I used and what I learned 👇
🧠 1. Transformers (Hugging Face)
 Used for the generation part of RAG — this provides access to powerful open-source LLMs that take the retrieved context and generate accurate, human-like responses. It’s the “brain” that crafts the final output.
🔍 2. Sentence-Transformers
 Responsible for converting text into dense vector embeddings — numerical representations that capture the meaning of text. This helps the system understand semantic similarity between a question and the stored documents.
⚡ 3. FAISS (Facebook AI Similarity Search)
 A vector search engine built by Meta AI, designed for lightning-fast similarity search across large datasets. It stores embeddings and retrieves the most relevant chunks of information in real-time.
🧩 4. LangChain
 I used LangChain’s Text Splitter to automatically divide documents into smaller, context-friendly chunks — saving hours of manual preprocessing. This ensures that each chunk fits within the model’s token limits.
🧠 How it all connects:
Split text → Embed → Index → Retrieve → Generate!
 LangChain splits → Sentence-Transformers embeds → FAISS retrieves → Transformers generate the final response.
💡 Key Takeaway:
 Building RAG from scratch gave me a deep understanding of how modern AI systems combine retrieval and generation to produce accurate, context-aware answers.

# SimpleRAG 🚀

SimpleRAG is a lightweight, AI-powered knowledge base chatbot. It provides a minimalist Retrieval-Augmented Generation (RAG) experience, allowing users to upload text documents and instantly converse with their data.

## 🛠️ Tech Stack

*   **Frontend UI:** [Streamlit](https://streamlit.io) — Powers the minimalist, interactive web chat interface.
*   **LLM Engine:** [OpenAI SDK] via [OpenRouter](https://openrouter.ai) — Handles text generation and embedding models with flexible model routing.
*   **Infrastructure:** The web application was deployed to Streamlit Community Cloud.

## ✨ Core Functionality

*   **Single-Format Ingestion:** Seamlessly accepts and parses uploaded plain text (`.txt`) files to construct the knowledge base.
*   **Advanced Retrieval:** Optimizes search accuracy by executing intermediate contextual retrieval steps on user queries before hitting the vector store.
*   **Frictionless Chat Experience:** Provides a fast, real-time interface for document-driven QA.

## 🚀 Getting Started

### Prerequisites
*   A Google account (for Google Colab)
*   An OpenRouter API key

### Deployment Workflow
1.  Open the project notebook inside Google Colab.
2.  Install the required dependencies (`streamlit`, `openai`, and tunneling utilities).
3.  Configure your OpenRouter API credentials.
4.  Run the Streamlit application code.
5.  Execute the tunneling script to generate a public URL.
6.  Click the generated link to launch the **SimpleRAG** interface.

---

## 🗺️ Future Roadmap
*   Migrate hosting to **Google Cloud Run** for serverless stability.
*   Implement **Google OAuth** to secure user access.
*   Integrate a persistent instance of **ChromaDB**.
*   Expand document ingestion to support Microsoft Word (`.docx`) files.

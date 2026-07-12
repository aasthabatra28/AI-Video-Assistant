# 🎬 AI Video Assistant

An AI-powered assistant that analyzes YouTube videos and local audio/video files using **Whisper**, **Mistral AI**, **LangChain**, and **ChromaDB**. It automatically generates meeting notes and lets users chat with the transcript using Retrieval-Augmented Generation (RAG).

---

## ✨ Features

- 🎥 Accepts YouTube URLs and local audio/video files
- 🎙️ Converts speech to text using OpenAI Whisper
- 📝 Generates an AI-powered title and concise summary
- ✅ Extracts action items from the conversation
- 🔑 Identifies key decisions discussed
- ❓ Detects open questions and follow-ups
- 🧠 Creates embeddings and stores them in ChromaDB
- 💬 Enables conversational Q&A over the transcript using RAG
- 🖥️ Interactive Streamlit interface for easy use

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Mistral AI
- OpenAI Whisper
- ChromaDB
- HuggingFace Embeddings
- yt-dlp
- pydub

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📂 Project Structure

- `app.py` – Streamlit interface
- `main.py` – Main application pipeline
- `audio_processor.py` – Audio extraction and preprocessing
- `transcriber.py` – Whisper transcription
- `summarize.py` – Title and summary generation
- `extractor.py` – Action items, decisions, and questions
- `vector_store.py` – ChromaDB vector store
- `rag_engine.py` – RAG pipeline and chat functionality

---

## 📄 License

This project is licensed under the MIT License.

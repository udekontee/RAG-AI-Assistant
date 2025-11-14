# RAG-AI-Assistant

# 🤖 The RAG-AI-Assistant
<img width="818" height="284" alt="image" src="https://github.com/user-attachments/assets/79ce3c41-d55a-4dd3-aef6-235975320f4d" />

**A preview of The RAG-AI-Assistant interface built with Gradio.**

---

**An intelligent Retrieval-Augmented Generation (RAG) assistant powered by FAISS, FLAN-T5, and Gradio.**  
This AI assistant retrieves accurate information from a local knowledge base and generates context-aware responses using advanced NLP models.

---

## 🚀 Project Overview
The **RAG-AI-Assistant** demonstrates how to combine *retrieval-based search* with *generative AI models* to produce factual, coherent answers.  
By leveraging the Natural Questions dataset, FAISS embeddings, and FLAN-T5’s reasoning power, it can efficiently retrieve relevant content and generate meaningful answers in natural language.

---

## ✨ Key Features
- 🔍 **Context Retrieval:** FAISS-based semantic search for relevant knowledge.
- 🧠 **Answer Generation:** Powered by FLAN-T5 (T5 fine-tuned for reasoning and dialogue).
- 💬 **Interactive UI:** Real-time chat-like interface built with Gradio.
- 📚 **Dataset Integration:** Uses Kaggle’s Natural Questions dataset.
- ⚙️ **End-to-End Workflow:** From data ingestion to model inference — all in one notebook.

---

## 🧩 Tech Stack

| Component | Purpose |
|------------|----------|
| **Python** | Core language |
| **FAISS** | Vector database for retrieval |
| **Transformers (FLAN-T5)** | Model for generative responses |
| **SentenceTransformers** | Creates text embeddings |
| **Gradio** | Interactive front-end |
| **KaggleHub** | Access to public datasets |

---

### ⚙️ Installation & Setup

### Clone the repository
git clone https://github.com/your-username/The-RAG-AI-Assistant.git
cd The-RAG-AI-Assistant

### Install dependencies
pip install -r requirements.txt

### Launch Jupyter Notebook
jupyter notebook The_RAG_AI_Assistant.ipynb

## 💻 How It Works
Download the Dataset
import kagglehub
path = kagglehub.dataset_download("frankossai/natural-questions-dataset")

## 🧠 Example Usage
Inside Jupyter **demo.launch(debug=True)**
- Who discovered penicillin? **Alexander Fleming**
- When did Apollo 11 land on the moon? **1969**
- Who is the president of Nigeria? **Bola Ahmed Tinubu**
  
---

## 🏁 Conclusion

The RAG-AI-Assistant demonstrates how retrieval-augmented generation can be applied for question-answering tasks using open-source models and simple infrastructure.
It’s a great foundation for extending toward larger document retrieval, custom knowledge bases, or API-connected assistants.




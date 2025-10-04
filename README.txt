🧠 PDF Chatbot using LangChain, OpenAI, and Streamlit

An interactive AI-powered chatbot that allows users to upload PDF documents and ask questions directly about their content.
This project combines LangChain, FAISS vector search, and OpenAI GPT models to perform intelligent question answering over uploaded PDFs.

🚀 Features
---------------
📄 Upload any PDF and extract its content automatically
🔍 Chunk and embed text using RecursiveCharacterTextSplitter and OpenAIEmbeddings
🧩 Store and retrieve document vectors using FAISS
💬 Ask natural language questions about your document
🖥️ Simple and intuitive UI built with Streamlit

🛠️ Tech Stack
------------------
Python
Streamlit – for frontend interface
LangChain – for document processing and QA chain
OpenAI GPT – for generating intelligent answers
FAISS – for efficient vector similarity search

💡 How It Works
-------------------
Upload a PDF file.
The app extracts and splits the text into manageable chunks.
Each chunk is embedded and stored in a FAISS vector store.
When a user asks a question, the most relevant chunks are retrieved and passed to an OpenAI model for generating an accurate response.
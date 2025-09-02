# 📂 GenAI Document Management System 

A powerful AI-driven system to *upload, extract, translate, summarize, and search documents* with ease.  
Built with *FastAPI* and enhanced by *Gemini Flash 2.0 API* for advanced text intelligence.

---

## 🚀 Features

- 📤 *Document Upload* – Upload and manage PDF & DOCX files.
- 📝 *Text Extraction* – Extract text using pdfminer.six and python-docx.
- 🌍 *Translation* – Translate text into multiple languages with *Gemini Flash 2.0 API*.
- ✂ *Summarization* – AI-powered document summarization.
- 🔍 *Search* – Find documents by title, tags, or uploader.
- 🔡 *Transliteration* – Convert text into different scripts.
- 🖼 *Image Extraction* – Extract images from PDF/DOCX.
- 🔐 *User Authentication* – Registration, login & OTP verification.
- 📜 *Activity Logs* – Track user actions in the database.
- 💬 *Comments* – Add comments for collaboration.
- ❓ *QnA* – Ask questions on document content (AI-powered).

---
## ⚙ Tech Stack  

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)  
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green?logo=fastapi)  
![Streamlit](https://img.shields.io/badge/Streamlit-UI-orange?logo=streamlit)  
![GeminiFlash 2.0](https://img.shields.io/badge/GeminiFlash-API_Powered-purple)  
![Uvicorn](https://img.shields.io/badge/Uvicorn-ASGI_Server-lightgrey?logo=uvicorn)  
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)  

---

## 📚 Key Libraries  

![pdfminer.six](https://img.shields.io/badge/pdfminer.six-PDF_Parsing-yellow)  
![python-docx](https://img.shields.io/badge/python--docx-Word_Processing-lightblue)  
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-red?logo=sqlalchemy)  
![PyJWT](https://img.shields.io/badge/PyJWT-Auth_Tokens-green)  
![passlib](https://img.shields.io/badge/passlib-Password_Hashing-blue)  
![requests](https://img.shields.io/badge/requests-HTTP_Requests-black?logo=python)  
![pydantic](https://img.shields.io/badge/pydantic-Data_Validation-teal)  


## 📂 Project Structure
<pre style="font-size:16px;">
📁 Document-Management-System/
├── 📄 app_fast_api.py # FastAPI backend entry
├── 📄 app_stream.py # Streamlit frontend entry
├── 📁 utility/
│   ├── 📄 document_upload.py
│   ├── 📄 extract_text.py
│   ├── 📄 translate_text.py
│   ├── 📄 summarize_text.py
│   ├── 📄 transliteration.py
│   ├── 🖼 extract_images.py
│   ├── 🔍 search.py
│   ├── 💬 comments.py
│   ├── ❓ qna.py
│   ├── 🔐 auth.py
│   └── 📜 logs.py
├── 📁 helpers/
│   ├── 📄 constants.py
│   └── 🗄 database.py
├── 📄 requirements.txt
├── 📄 README.md
└── 🔑 .env
</pre>

---

## 🪄✨ Summon the Server & Stream!
---
### Run FastAPI server
uvicorn main:app --reload  

---

### Run Streamlit app
streamlit run streamlit_app.py

---

## 📊 Deliverables

- ✅ FastAPI backend with AI-powered features  
- ✅ Document summarization & translation with *Gemini Flash 2.0*  
- ✅ Secure authentication & logging system  
- ✅ Search & QnA capabilities  
- ✅ Ready-to-use API & UI demo  

---

## ✨ Future Enhancements  

- 🔍 Advanced semantic search with vector databases (FAISS / Pinecone)  
- 🌍 Multi-language document support  
- 📦 Cloud deployment (AWS/GCP/Azure)  
- 🤖 Fine-tuned summarization models for domain-specific docs  
- 📊 Enhanced analytics dashboard  

---

## 👤 Author  
**Piyush Pachare**  
 

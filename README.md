# DocuMind - MultiPDF Chatbot  
A chatbot that answers questions from your PDFs using AI-powered natural language processing.  

## 🚀 Introduction  
DocuMind is an advanced AI assistant that allows users to chat with multiple PDF documents. It processes PDFs, understands their content, and provides intelligent answers based on user queries. Built using **LangChain, OpenAI, Hugging Face, and Streamlit**, this project enhances document-based interactions with voice-assisted responses.  

## 🛠 Features  
✅ **Chat with Multiple PDFs** – Ask questions and get context-aware responses.  
✅ **AI-Powered Search** – Uses embeddings for accurate results.  
✅ **Voice-Assisted Responses** – Get spoken answers for a seamless experience.  
✅ **Supports Diverse Data Sources** – Load PDFs, Excel files, Google Drive documents, and more.  
✅ **Built with LangChain & Hugging Face** – For improved AI-driven responses.  

## 🔍 How It Works  
1️⃣ **PDF Upload** – Load multiple PDFs into the chatbot.  
2️⃣ **Text Processing** – Extracts and chunks text for efficient retrieval.  
3️⃣ **Embedding & Similarity Matching** – Finds the most relevant text based on your query.  
4️⃣ **AI Response Generation** – Uses OpenAI’s GPT to generate accurate answers.  
5️⃣ **Voice Output** – Responds with text and voice.  

## 📦 Installation  
Follow these steps to set up and run **DocuMind**:  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/ankurkr07/DocuMind.git
cd DocuMind
```
### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Add API Key
Create a .env file in the project directory and add your OpenAI API Key:
```bash
OPENAI_API_KEY=your_secret_api_key
```
### ▶️ Usage
Start the chatbot using Streamlit:
```bash
streamlit run app.py
```
Load your PDFs.
Ask questions in natural language.
Receive intelligent responses from the document’s content.





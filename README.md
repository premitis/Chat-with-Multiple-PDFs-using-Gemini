# 📄 Chat with Multiple PDFs using Gemini 💬


Welcome to the Chat with Multiple PDFs using Gemini project! This Streamlit web application allows you to interact with the content of multiple PDF documents using Langchain's conversational chain and Google GenAI embeddings.

✨ Features


1. Upload Multiple PDFs: Easily upload and manage multiple PDF documents
2. Interactive Q&A: Ask questions about the content of your PDFs and receive detailed answers.
3. Advanced NLP: Utilizes Langchain's conversational chain and Google GenAI embeddings for accurate and context-aware responses.

🚀 Installation


1) Clone the Repository
2) Install Dependencies:
Copy and paste the following command into your terminal:
pip install -r requirements.txt
3) Set Up Environment Variables:
Create a .env file in the project directory and add your Google API key:
GOOGLE_API_KEY=your_google_api_key

📖 Usage


Run the Streamlit Application:
1) Copy and paste the following command into your terminal:
streamlit run app.py
2) Open in Browser:
Open the URL provided by Streamlit in your web browser.
3) Upload PDF Files:
Use the file uploader in the sidebar to upload your PDF documents.
4) Ask Questions:
Enter your questions in the text input box and receive detailed answers based on the content of your PDFs.

🛠 Dependencies


1. Streamlit: For creating the web application.
2. PyPDF2: For reading PDF files.
3. Langchain: For managing text chunks and the conversational chain.
4. Langchain Google GenAI: For embeddings and conversational models.
5. dotenv: For loading environment variables

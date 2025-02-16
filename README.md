# ARIA - AI-based Research and Interpretation Assistant 🚀

ARIA (AI-based Research and Interpretation Assistant) is a powerful AI-powered tool designed to assist users in extracting, interpreting, and interacting with information from a wide variety of file formats. Built using **Streamlit**, **LangChain**, and **Hugging Face**, ARIA can process documents, images, audio, and more, making it an ideal assistant for researchers, students, and professionals.

---

## Features

- **Multi-Format Support**: Extract text from **PDFs**, **Word documents**, **Excel sheets**, **PowerPoint presentations**, **images**, **audio files**, and more.
- **AI-Powered Conversations**: Interact with the assistant using natural language to ask questions and get insights from uploaded files.
- **Online and Offline Modes**: 
  - **Online Mode**: Uses the **Mistral-8x22B-Instruct-v0.1** model via the Together API for advanced AI capabilities.
  - **Offline Mode**: Uses the **Sol model** (ChatOllama) for local, offline interactions.
- **File Processing**: Automatically processes uploaded files and creates a searchable knowledge base using **FAISS** vector embeddings.
- **User-Friendly Interface**: Built with **Streamlit**, ARIA provides an intuitive and interactive web interface.

---

## Supported File Formats

ARIA supports the following file formats for text extraction:
- **Documents**: PDF, DOCX, TXT, Markdown, LaTeX
- **Spreadsheets**: XLS, XLSX, CSV
- **Presentations**: PPTX
- **Code Files**: Python, Java, C, C++, JavaScript, Swift, R, Rust, SQL
- **Images**: JPG, JPEG, PNG, BMP (using OCR via Tesseract)
- **Audio**: WAV (using speech-to-text)
- **Archives**: ZIP, RAR
- **Web Files**: HTML, CSS, XML, JSON

---

## How It Works

1. **File Upload**: Users upload one or more files through the Streamlit interface.
2. **Text Extraction**: ARIA extracts text from the uploaded files using specialized libraries like PyPDF2, pytesseract, and BeautifulSoup.
3. **Text Chunking**: The extracted text is split into smaller chunks for efficient processing.
4. **Vector Embeddings**: Text chunks are converted into vector embeddings using **Hugging Face's Sentence Transformers**.
5. **Conversational AI**: Users can ask questions about the uploaded files, and ARIA uses a **Conversational Retrieval Chain** to provide accurate and context-aware responses.
6. **Chat History**: ARIA maintains a conversation history, allowing users to interact naturally.

---

## Installation

To run ARIA locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/ARIA.git
   cd ARIA
---

## Usage
Upload Files:
Use the sidebar to upload one or more files.

Click the NEXT button to process the files.

Ask Questions:
Once the files are processed, type your question in the chat input box.

ARIA will provide answers based on the content of the uploaded files.

Switch Modes:
Toggle between Online Mode (for advanced AI capabilities) and Offline Mode (for local processing).

---
## Future Enhancements

Support for More File Formats: Add support for additional file types.

Enhanced OCR: Improve image text extraction with advanced OCR techniques.

Multi-Language Support: Add support for non-English languages.

Cloud Deployment: Deploy ARIA on cloud platforms like AWS or streamlit.

User Authentication: Add user authentication and file storage for persistent sessions.

---
## Contributing

Contributions are welcome! If you'd like to contribute to ARIA, please follow these steps:

Fork the repository.

Create a new branch for your feature or bugfix.

Submit a pull request with a detailed description of your changes.

---

## Contact
For questions or feedback, feel free to reach out:

Name: Adhiraj Pawar

Email: adhirajpawar1124@gmail.com

LinkedIn: https://www.linkedin.com/in/adhiraj-pawar/

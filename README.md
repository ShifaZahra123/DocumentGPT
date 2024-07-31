# DocumentGPT: Conversational AI for Document Analysis

**DocumentGPT** is an interactive Streamlit application designed to provide **conversational insights** from your uploaded documents. Leveraging state-of-the-art NLP models, DocumentGPT allows you to **ask questions** and receive **answers directly from your PDFs and DOCX files**.

## **Features**

- **Easy Document Upload**: Upload multiple PDF and DOCX files effortlessly.
- **Natural Language Queries**: Interact with your documents through intuitive, natural language questions.
- **Text Embedding and Retrieval**: Uses `sentence-transformers` for efficient text embedding and `FAISS` for semantic search.
- **Open-Source Language Models**: Utilizes free and open-source models, making it accessible and cost-effective.
- **Responsive UI**: Built with Streamlit, ensuring a user-friendly and interactive experience.

## **Getting Started**

To run DocumentGPT locally, ensure you have Python 3.7+ installed. Clone the repository and install the required packages listed in `requirements.txt`:

```bash
git clone https://github.com/yourusername/DocumentGPT.git
cd DocumentGPT
pip install -r requirements.txt

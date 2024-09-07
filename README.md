# TextSummarizer

## AI Text and Document Summarizer
This AI-powered text and document summarizer is built using Streamlit and the txtai library. It allows users to input text or upload PDF documents and generates concise summaries. The summarizer works by leveraging natural language processing models to extract the most important points from the content. Instead of using OpenAI's API, this app utilizes txtai's Summary pipeline, an open-source AI framework that enables natural language understanding and document indexing. The app is highly efficient for summarizing both short texts and lengthy documents, providing users with a quick overview of the essential information.

## Installation

1. Clone the repository `https://github.com/Centrix3009/Text-Summarizer.git`
2. Setup your virtual environment: `python -m venv venv`
3. Activate the virtual environment `.\venv\Scripts\Activate`
4. install all packages and dependencies `pip install -r requirements.txt`
   If there's an issue, install libraries manually : `pip install streamlit`
                                                     `pip install txtai`
                                                     `pip install PyPDF2`  
5. run the website: `streamlit run app.py`

## Snippet

![Summarizer](https://github.com/user-attachments/assets/dbaf1c51-9748-4794-9573-4bee5c330a29)

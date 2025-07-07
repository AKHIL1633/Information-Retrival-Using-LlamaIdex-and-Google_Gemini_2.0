# Information Retrieval Using LlamaIndex and Google Gemini

A cutting-edge information retrieval system that combines the power of **LlamaIndex** and **Google Gemini** for efficient, intelligent document search and question answering with a user-friendly interface.

---

## 🚀 Features

- **Document Indexing:** Fast and scalable document ingestion using LlamaIndex.
- **Question Answering:** Natural language Q&A using Google Gemini LLM.
- **PDF Support:** Upload and search within your own PDF files.
- **Web UI:** Streamlit app for interactive querying and exploration.
- **Experiment Tracking:** Store and analyze query logs.

---

## 📁 Project Structure

Data/ # Raw and processed data files
Experiments/ # Experiment scripts and notebooks
QAWithPDF/ # Core QA and PDF modules
QApplication.egg-info/
pycache/
build/
dist/
logs/ # Logs and results
notebook/ # Jupyter notebooks
storage/ # Persistent storage
exception.py
logger.py
requirements.txt
setup.py
StreamlitApp.py # Main Streamlit web app
template.py


---

## ⚙️ Setup Instructions

1. **Clone this repository**
    ```sh
    git clone https://github.com/AKHIL1633/Information-Retrival-Using-LlamaIdex-and-Google_Gemini_2.0.git
    cd Information-Retrival-Using-LlamaIdex-and-Google_Gemini_2.0
    ```

2. **Create and activate Conda environment**
    ```sh
    conda create -n llama_env python=3.9
    conda activate llama_env
    ```

3. **Install dependencies**
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**
    ```sh
    streamlit run StreamlitApp.py
    ```

---

## 🧠 Technologies Used

- Python 3.9
- LlamaIndex
- Google Gemini API
- Streamlit
- PyPDF2 or similar for PDF handling
- Logging, Exception Handling


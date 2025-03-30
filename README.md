# YouTube RAG

A Python-based tool for extracting, transcribing, and analyzing YouTube video content using RAG (Retrieval-Augmented Generation) techniques.

## Features

- YouTube video content extraction
- Audio transcription using OpenAI's Whisper
- Vector storage and retrieval using Pinecone
- Integration with LangChain for RAG implementation
- Interactive Jupyter notebook support

## Prerequisites

- Python 3.12 or higher
- FFmpeg installed on your system
- OpenAI API key
- Pinecone API key

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd youtube-rag
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
```

3. Install dependencies using uv:
```bash
uv pip install -r requirements.txt
```

## Environment Setup

Create a `.env` file in the project root with the following variables:
```
OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
PINECONE_ENVIRONMENT=your_pinecone_environment
```

## Project Structure

- `main.py`: Main entry point for the application
- `notebook.ipynb`: Jupyter notebook for interactive development
- `transcription.txt`: Output file for video transcriptions
- `pyproject.toml`: Project dependencies and metadata
- `.env`: Environment variables (not tracked in git)

## Usage

1. Run the main script:
```bash
python main.py
```

2. For interactive development, launch the Jupyter notebook:
```bash
jupyter notebook notebook.ipynb
```

## Dependencies

- docarray: For document processing
- ffmpeg: For audio processing
- langchain-community: For RAG implementation
- langchain-openai: OpenAI integration
- langchain-pinecone: Pinecone vector store integration
- openai-whisper: For audio transcription
- pytube: YouTube video downloading
- scikit-learn: For machine learning utilities
- tiktoken: For token counting

## Development

This project uses:
- Ruff for linting
- uv for dependency management
- Python 3.12+ for modern Python features

## License


## Contributing



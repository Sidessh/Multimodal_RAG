---

# Video Intelligence RAG Platform

This project implements a multimodal Retrieval-Augmented Generation (RAG) system that converts video content into images, audio, and text for intelligent retrieval and query response. It integrates LlamaIndex and LanceDB for efficient data storage and indexing, and utilizes GPT-4 Vision for generating responses based on the multimodal data.

## Features
- Converts video into images, audio, and transcribed text.
- Uses LlamaIndex and LanceDB to index and store multimodal data.
- Employs GPT-4 Vision for intelligent query response generation, integrating multiple data types (images, audio, text).

## Tech Stack
- **LlamaIndex**: For indexing and retrieval of multimodal data.
- **LanceDB**: Used as the vector store for embeddings.
- **GPT-4 Vision**: For generating responses based on multimodal input.
- **MoviePy**: To process video files and extract images/audio.
- **SpeechRecognition**: For transcribing audio to text.
- **Pytube**: To download video content from YouTube.


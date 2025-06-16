# Meeting Minutes Summarizer (Audio to Summary)

## Introduction

This project is an interactive Google Colab notebook that allows users to **summarize meeting minutes directly from audio recordings**. Just upload your MP3 file—the notebook uses **OpenAI’s Whisper model** for transcription, then generates a concise summary with **LLAMA via Hugging Face**. Everything runs in an easy Gradio web app, fully leveraging Colab’s free GPU support.

## Table of Contents

- [Introduction](#introduction)
- [Workflow](#workflow)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Workflow

```
Upload MP3 File 
      ↓
Transcription (OpenAI Whisper)
      ↓
Text Summarization (LLAMA, Hugging Face)
      ↓
Summary Output (Gradio Interface)
```

## Features

- **Audio to Summary:** Upload meeting audio (.mp3) and get a concise summary.
- **State-of-the-art Models:**
  - **OpenAI Whisper** for accurate audio transcription.
  - **Llama (Hugging Face)** for advanced text summarization.
- **Intuitive Gradio Web Interface**
- **Google Colab with GPU Acceleration**
- **Easy Authentication** for secure model access.

## Installation

1. **Open the notebook in [Google Colab](https://colab.research.google.com/).**
2. Run all cells in order—dependencies install automatically.

## Usage

1. **Authenticate:**  
   - Enter your **OpenAI API key** (for Whisper) and **Hugging Face token** (for LLAMA) when prompted.
2. **Launch Gradio App:**  
   - The notebook will start a Gradio web app.
3. **Upload your MP3 file:**  
   - Use the interface to upload your meeting audio.
4. **Receive your summary:**  
   - The app will show the transcription and a summarized version.

## Dependencies

- `gradio`
- `torch`
- `transformers`
- `openai` *(for Whisper)*
- `huggingface_hub` *(for Llama)*
- `google.colab`

## Configuration

- **OpenAI API Key:** Needed for Whisper transcription.
- **Hugging Face Access Token:** Needed for LLAMA summarization.
- You will enter these securely in the notebook.

## Documentation

- **Notebook File:**  
  All code and documentation are in [meeting_minutes_gradio.ipynb](./meeting_minutes_gradio.ipynb).
- **Model Links:**  
  - [OpenAI Whisper](https://platform.openai.com/docs/guides/speech-to-text)
  - [LLAMA on Hugging Face](https://huggingface.co/models?search=llama)

## Troubleshooting

- **Authentication Issues:**  
  - Ensure your API keys are correct and accounts are active.
- **Audio Errors:**  
  - Make sure your file is .mp3 format and under Colab’s upload size limit.
- **Out of Memory:**  
  - Try shorter audio or ensure Colab is set to GPU.
- **Gradio UI Not Loading:**  
  - Run all cells in order and check Colab connection.

## Contributors

- *Open Source Community*  

## License

This project is licensed under the **MIT License**.


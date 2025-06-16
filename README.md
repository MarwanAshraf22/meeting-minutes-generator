# Meeting Minutes Summarizer (Google Colab + Gradio)

## Introduction

This project provides an interactive Google Colab notebook that helps users **summarize meeting minutes** using advanced AI models. With an easy-to-use [Gradio](https://gradio.app/) interface, users can upload their meeting audio file and receive concise summaries. The notebook supports both OpenAI and HuggingFace models and takes advantage of GPU acceleration available in Google Colab.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Features

- **Summarize meeting minutes automatically**
- **Interactive Gradio web UI**
- **Supports both OpenAI and HuggingFace models**
- **GPU acceleration via Google Colab**
- **Easy authentication for secure access to models**

## Installation

1. **Open the notebook in [Google Colab](https://colab.research.google.com/).**
2. Run all cells in order. The notebook will handle package installation automatically.

## Usage

1. **Authenticate**  
   - Enter your **OpenAI API key** and/or **HuggingFace access token** when prompted in the notebook.
2. **Start the Gradio Interface**  
   - The notebook will launch a Gradio web app for you to upload meeting transcripts and view summaries.
3. **Upload your meeting minutes**  
   - Use the Gradio interface to upload text files or paste your meeting content.
4. **Receive a summary**  
   - The AI model will generate a summary of your meeting.

## Dependencies

- `gradio`
- `torch`
- `transformers`
- `openai`
- `huggingface_hub`
- `google.colab`

All dependencies are installed automatically when running in Google Colab.

## Configuration

- **API Keys Required**  
  - **OpenAI API Key:** For using OpenAI models  
  - **HuggingFace Access Token:** For using HuggingFace models  
- You will be prompted to input these securely in the notebook.

## Documentation

- **Notebook File:**  
  The main code and documentation are in the [meeting_minutes_gradio.ipynb](./meeting_minutes_gradio.ipynb) notebook.
- **Gradio:**  
  Learn more about Gradio at [gradio.app](https://gradio.app/)

## Troubleshooting

- **Authentication Errors:**  
  - Double-check your API keys and make sure your HuggingFace and OpenAI accounts are active.
- **Out of Memory:**  
  - Try using a smaller model or ensure you’re using a GPU runtime in Colab.
- **Gradio UI Not Loading:**  
  - Make sure all cells have been run in order, and that Colab hasn’t disconnected.

## Contributors

- *Open Source Community*  

## License

This project is licensed under an **open source** license (please specify if you want [MIT](https://opensource.org/licenses/MIT), [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0), etc.).

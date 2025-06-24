# Ollama Streamlit Chat Application

A modern, user-friendly chat interface for interacting with local Large Language Models (LLMs) through Ollama. This Streamlit application provides real-time streaming responses, model selection, and configurable chat settings.

## Features

* 🤖 Multiple Model Support: Automatically detects and allows selection of available Ollama models
* 💬 Real-time Chat Interface: Clean, intuitive chat UI with message history
* 🔄 Streaming Responses: Live streaming of model responses for better user experience
* ⚙ Configurable Settings: Adjustable temperature control for response creativity
* 🔌 Connection Monitoring: Real-time connection status with Ollama service
* 🗑 Chat Management: Clear chat history and session management
* 🚨 Error Handling: Comprehensive error handling and user feedback

## Installation

### Option 1: Clone from GitHub (Recommended)

bash
git clone https://github.com/Sanjana-1909/Ollama-asst.git


## Prerequisites

### 1. Ollama Installation

Windows:

bash
# Download and install from https://ollama.ai/download


macOS:

bash
brew install ollama


Linux:

bash
curl -fsSL https://ollama.ai/install.sh | sh


### 2. Start Ollama Service

bash
ollama serve


### 3. Download Models

bash
ollama pull llama2
ollama pull mistral
ollama pull codellama
ollama pull phi
ollama pull neural-chat


## Quick Start

### 1. Clone the Repository

bash
git clone https://github.com/Sanjana-1909/Ollama-asst.git


### 2. Setup Virtual Environment

cmd
create_venv.bat


### 3. Manual Activation (for future sessions)

cmd
activate.bat


### 4. Run the Application

cmd
streamlit run Ollama_asst.py


The application will open in your browser at http://localhost:8501.

## Configuration

Edit the OLLAMA_BASE_URL variable in Ollama_asst.py:

python
OLLAMA_BASE_URL = "http://your-host:your-port"


## License

This project is licensed under the MIT License.

## Acknowledgments

* [Ollama](https://ollama.ai/) for providing the local LLM platform
* [Streamlit](https://streamlit.io/) for the amazing web app framework
* Open source LLM community for the models

Thank you for checking out this project!

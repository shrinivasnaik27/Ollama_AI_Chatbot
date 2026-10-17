# Ollama AI Chatbot

A simple, interactive AI chatbot built using Python and Ollama. It uses the Qwen3.5 0.8B language model to generate responses and maintain conversation history during a chat session.

## Features

- Interactive command-line chat interface.
- Powered by the Qwen3.5 0.8B AI model.
- Maintains conversation history during the session.
- Simple and informative AI responses.
- Customizable response temperature.
- Runs locally using Ollama.
- Type `exit` to end the conversation.

## Technologies Used

- Python
- Ollama
- Qwen3.5 0.8B

## Requirements

- Python 3.10 or later recommended.
- Ollama installed on your computer.
- Qwen3.5 0.8B model downloaded.
- Python Ollama library.

## Installation

### 1. Install Python

Download Python from the official website:

https://www.python.org/downloads/

### 2. Install Ollama

Download Ollama from:

https://ollama.com/download

### 3. Download the AI Model

Open your terminal or command prompt and run:

```bash
ollama pull qwen3.5:0.8b
```

### 4. Install the Required Python Library

```bash
pip install ollama
```

### 5. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate into the project folder:

```bash
cd YOUR_PROJECT_FOLDER
```

Replace the example values with your actual GitHub repository URL and folder name.

## Usage

Make sure Ollama is running on your computer. Then run your Python file:

```bash
python chatbot.py
```

Replace `chatbot.py` with your actual Python filename if it is different.

Start typing your questions to chat with the AI.

To stop the chatbot, type:

```text
exit
```

## How It Works

The chatbot connects to the local Ollama server and sends user messages to the Qwen3.5 0.8B model. It stores user messages and AI responses in conversation history, allowing the model to use earlier messages as context when generating subsequent answers.

The response temperature is configured to `2`, which allows highly varied outputs but may also make responses less consistent.

## Project Structure

```text
Ollama-AI-Chatbot/
├── chatbot.py
└── README.md
```

The Python filename shown above is an example. Use your actual filename.

## Future Improvements

- Add a graphical user interface.
- Support clearing or saving conversation history.
- Add configurable model selection.
- Improve error handling when Ollama is unavailable.
- Add support for streaming responses.

## License

This project is available for educational and personal use. Add a license file if you want to specify formal reuse and distribution terms.

## Author

Developed as a Python and local AI chatbot project.
